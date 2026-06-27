# Regression-Based Business Insights & Model Interpretation

## Business Problem Summary

This project analyzes a retail business dataset to identify the factors associated with monthly sales using regression analysis. The objective is to understand how different business variables influence sales and provide recommendations that support better business decisions.

---

## Dataset Description

The dataset contains monthly performance data for retail stores, including information on marketing spend, customer footfall, inventory availability, discounts, customer ratings, store regions, and monthly sales.

---

## Dataset Understanding

### Dependent Variable

* **Monthly Sales**

This is the target variable that the regression models aim to predict.

---

### Potential Independent Variables

* Marketing Spend
* Footfall
* Average Discount Percentage
* Inventory Availability Percentage
* Customer Rating
* Region (Dummy Variables)

---

### Numerical Variables

* Marketing Spend
* Footfall
* Average Discount Percentage
* Inventory Availability Percentage
* Customer Rating
* Monthly Sales

---

### Categorical Variables

* Region
* Store Type

---

### Variables Requiring Cleaning or Transformation

* Missing values were checked and handled where required.
* The **Region** variable was converted into dummy variables for regression analysis.
* One category was excluded to avoid the dummy variable trap.
* If needed, date variables should be converted into meaningful features such as month or quarter.

---

### Variables Not Useful for Regression

* **Store ID** was treated as an identifier and excluded from the regression model because it does not provide predictive information.

---

## Regression Approach

Two simple linear regression models and one multiple linear regression model were developed.

### Simple Regression Models

* Monthly Sales vs. Marketing Spend
* Monthly Sales vs. Inventory Availability Percentage

### Multiple Regression Model

The final model included:

* Footfall
* Average Discount Percentage
* Customer Rating
* Region Dummy Variables (South, East, and West)

The **North** region was used as the reference category.

---

## Dummy Variable Approach

The categorical variable **Region** was converted into dummy variables.

Dummy variables created:

* South
* East
* West

Reference category:

* **North**

The reference category was omitted from the regression model to prevent perfect multicollinearity (dummy variable trap).

---

## Model Comparison Summary

The simple regression models explain the relationship between monthly sales and individual business variables. The multiple regression model provides a better explanation of monthly sales because it considers several business factors simultaneously. Based on the higher R-squared value and better predictive performance, the multiple regression model was selected as the final model.

---

## Final Model Selected

**Multiple Linear Regression**

The final model was selected because it provides stronger explanatory power and better supports business decision-making by incorporating multiple important variables.

---

## Business Recommendation

The analysis suggests that leadership should focus on increasing customer footfall, improving customer satisfaction, and investing in effective marketing activities. Regional differences should be interpreted carefully because they were not consistently statistically significant.

---

## Assumptions and Limitations

* The regression model assumes linear relationships between variables.
* External factors such as competition, seasonality, weather, and local events are not included.
* Regression identifies statistical associations but does not prove causation.
* Business decisions should combine regression insights with operational knowledge.

---

## Repository Structure

```
part3_regression_insights/
├── data/
├── analysis/
├── outputs/
├── screenshots/
└── README.md
```

---

## Screenshots Included

* Simple Regression Output
* Multiple Regression Output
* Residual Analysis Preview
* Model Comparison Preview
