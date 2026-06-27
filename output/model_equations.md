# Model Equations

## Simple Regression Equations

### Model 1: Marketing Spend

**Equation**

**Monthly Sales = 560777.35 + (2.13 × Marketing Spend)**

**Business Interpretation**

For every one-unit increase in marketing spend, monthly sales are expected to increase by approximately **2.13 units**, assuming all other factors remain unchanged. This indicates that marketing investment has a positive relationship with sales performance.

---

### Model 2: Inventory Availability

**Equation**

**Monthly Sales = 484814.26 + (2217.83 × Inventory Availability %)**

**Business Interpretation**

A higher inventory availability percentage is associated with higher monthly sales. Maintaining product availability helps reduce missed sales opportunities and improves customer satisfaction.

---

# Multiple Regression Equation

**Monthly Sales = 423677.56 + (35.88 × Footfall) − (87972.99 × Average Discount %) + (8866.34 × Customer Rating) + (7755.69 × South) − (13350.28 × East) + (4418.60 × West)**

*(North is the reference category.)*

---

# Explanation of Each Coefficient

| Variable                   | Business Meaning                                                                                                                                 |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Intercept**              | Estimated monthly sales when all predictor variables are zero. It provides the baseline value for the model.                                     |
| **Footfall**               | A positive coefficient indicates that stores with more customer visits are expected to generate higher monthly sales.                            |
| **Average Discount %**     | A negative coefficient suggests that larger discounts are associated with lower monthly sales value, possibly due to reduced revenue per sale.   |
| **Customer Rating**        | Higher customer ratings are associated with increased monthly sales, indicating that customer satisfaction supports better business performance. |
| **South (Dummy Variable)** | Sales for stores in the South region are estimated relative to the North region while keeping other variables constant.                          |
| **East (Dummy Variable)**  | Represents the estimated sales difference between East and North stores.                                                                         |
| **West (Dummy Variable)**  | Represents the estimated sales difference between West and North stores.                                                                         |

---

# Dummy Variables

The categorical variable **Region** was converted into dummy variables.

Dummy variables created:

* South
* East
* West

**Reference Category:** **North**

The North region was excluded from the regression model to avoid the dummy variable trap (perfect multicollinearity). All regional coefficients are interpreted relative to the North region.

---

# Final Model Selected

**Multiple Linear Regression**

---

# Reason for Selecting the Final Model

The Multiple Linear Regression model was selected because it explains a much larger proportion of the variation in monthly sales (**R² = 0.7520**) than the simple regression models. It considers multiple business factors simultaneously, including customer footfall, discounts, customer ratings, and regional differences. As a result, it provides more reliable insights for business planning and supports better decision-making than models based on a single predictor.
