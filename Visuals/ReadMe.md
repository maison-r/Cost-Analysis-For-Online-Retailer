#  Visualizations: Campaign Cost-Benefit Analysis

This document provides a detailed explanation of the visualizations used in the `cost_analysis.ipynb` notebook. These charts are designed to support decision-making by illustrating how various cost components contribute to the overall marketing campaign budget.

---

## Visual Breakdown

### 1. **Bar Chart: Campaign Cost Components**

**Description:**  
Displays the cost of each component involved in the campaign — including email, SMS, design, ad spend, and coupon redemptions.

**Purpose:**  
Helps stakeholders quickly identify which parts of the campaign are most expensive, and where cost reductions may be possible.

**Example:**
- Y-axis: Cost (in dollars)
- X-axis: Cost categories (e.g., Email, SMS, Design, Coupons, Ad Spend)

---

### 2. **Pie Chart: Cost Distribution**

**Description:**  
Visualizes the percentage share of each cost component in the total campaign budget.

**Purpose:**  
Useful for presenting a clear picture of cost proportions — ideal for business presentations or reports.

---

### 3. **Scenario Comparison**

**Description:**  
This chart shows how the **total campaign cost changes** when the redemption rate or customer count is varied.

**Purpose:**  
Supports **what-if analysis** to test the impact of marketing assumptions on campaign costs.

---

## Tools Used

These charts are generated using:

- `matplotlib.pyplot` for bar/pie charts
- `pandas` for data handling
- `seaborn` (optional) for enhanced styling

Install with:

```bash
pip install matplotlib pandas seaborn

