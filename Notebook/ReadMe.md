#  Campaign Cost-Benefit Analysis Notebook

This Jupyter notebook performs a comprehensive cost-benefit analysis for a digital marketing campaign. It calculates the financial impact of marketing activities like email and SMS delivery, coupon redemptions, design work, and advertising spend.

---

##  What This Notebook Does

- Estimates **total campaign cost** based on configurable parameters
- Breaks down costs into:
  - Email cost
  - SMS cost
  - Design fee
  - Ad spend
  - Discount cost from redemptions
- Allows **scenario exploration** by adjusting parameters like:
  - Redemption rate
  - Customer count
  - Message cost
- Visualizes results with simple bar charts and summaries

---

##  Parameters You Can Modify

In the first code block, you can change the following values to simulate different marketing scenarios:

```python
email_cost_per = 0.01                 # Cost per email sent
sms_cost_per = 0.05                   # Cost per SMS sent
design_cost = 300                     # One-time design cost
discount_per_redemption = 5          # Discount value per coupon
expected_redemption_rate = 0.10      # Assumed redemption rate (e.g., 10%)
ad_spend = 750                        # Additional advertising spend
num_customers = 5000                 # Number of customers targeted
