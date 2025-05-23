
# Customer Churn Discount Strategy – Revenue Impact Analysis

## Objective

To evaluate the revenue impact of a strategy where a **20% discount** is offered to **high-risk-of-churn customers**, and to determine the **optimal churn probability threshold** (cut-off) to maximize retained revenue.

---

## Methodology

### Baseline Revenue Calculation (No Discount)

- Revenue is calculated using forecast electricity consumption, forecast price, and meter rent.
- For customers who churn, revenue is reduced by **91.9%** to account for partial-year retention.

### Intervention Strategy (With Discount)

- A discount is offered to customers above a selected churn probability threshold.
- **Key assumptions**:
  - All customers offered a discount accept it.
  - Discounted customers are fully retained (0% churn).
  - Non-discounted customers follow their actual churn outcomes.

### Revenue Delta Calculation

- Calculates the **difference in total revenue** between baseline and discount scenarios.
- Analyzes revenue deltas across a range of probability cut-offs to find the optimal threshold.

---

## Key Findings

### Optimal Cut-off Point (Simple Strategy)
- **Cut-off = 0.30**
- **Maximum revenue delta: $53,985.16**

### Value-Based Strategy (High Revenue Customers Only)
- Only customers with **base revenue > $500** receive a discount.
- **Cut-off = 0.29**, **Max delta: $27,207.70**
- Less effective due to smaller target group.

### Probability-Based Churn Forecast Strategy
- Uses predicted churn probabilities instead of actual churn outcomes.
- **Cut-off = 0.22**, **Max delta: $77,390.85**
- Most profitable approach among all tested.

### Model Calibration
- Calibration of churn probabilities is **acceptable**.
- No significant corrections (e.g., Platt scaling or isotonic regression) were applied.

---

## Insights & Recommendations

- A **20% discount** is effective at revenue retention **when targeted properly**.
- **Churn probability alone is not enough** — customer value (revenue potential) must also be factored in.
- Future directions:
  - **2D optimization**: jointly optimize discount level and cut-off probability.
  - Model **churn response as a function of discount level** to personalize offers and improve outcomes.

---

## Notes

- All calculations assume no change in electricity consumption due to price.
- Revenue effects are evaluated using **out-of-sample** predictions to avoid overfitting.

