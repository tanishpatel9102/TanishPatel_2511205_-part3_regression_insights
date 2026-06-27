# Residual Analysis

## Residual Calculation

The final multiple regression model was used to calculate the predicted monthly sales for each store.

* **Predicted Sales** were calculated using the final regression equation.
* **Residual** was calculated as:

**Residual = Actual Monthly Sales − Predicted Monthly Sales**

A positive residual indicates that the model under-predicted sales, while a negative residual indicates that the model over-predicted sales.

---

## Top 5 Largest Positive Residuals (Model Under-predicted Sales)

| Store ID | Actual Sales | Predicted Sales |   Residual |
| -------- | -----------: | --------------: | ---------: |
| STR-1028 |   713,611.16 |      585,787.84 | 127,823.32 |
| STR-1026 |   625,514.04 |      522,776.31 | 102,737.73 |
| STR-1051 |   787,715.51 |      687,108.58 | 100,606.93 |
| STR-1073 |   813,316.71 |      718,831.44 |  94,485.27 |
| STR-1064 |   799,046.94 |      706,037.59 |  93,009.35 |

### Business Interpretation

These stores generated higher sales than predicted by the regression model. This suggests that additional factors not included in the model—such as successful local promotions, favourable market conditions, customer loyalty, or store-specific operational strengths—may have contributed to stronger performance.

---

## Top 5 Largest Negative Residuals (Model Over-predicted Sales)

| Store ID | Actual Sales | Predicted Sales |    Residual |
| -------- | -----------: | --------------: | ----------: |
| STR-1017 |   685,379.08 |      841,689.02 | -156,309.94 |
| STR-1012 |   595,467.60 |      729,705.80 | -134,238.20 |
| STR-1023 |   627,171.90 |      757,371.68 | -130,199.78 |
| STR-1009 |   641,865.03 |      762,484.05 | -120,619.02 |
| STR-1077 |   538,376.00 |      648,422.56 | -110,046.56 |

### Business Interpretation

These stores recorded lower sales than predicted by the model. Possible reasons include inventory shortages, weaker local demand, operational challenges, increased competition, or temporary business disruptions that were not captured by the regression variables.

---

## Under-prediction and Over-prediction

The residual analysis indicates that the regression model both under-predicts and over-predicts sales for certain stores. No clear evidence suggests that a particular store type or region is consistently under- or over-predicted. Most prediction errors are likely due to business factors not included in the model, such as seasonal demand, local events, competitor activities, or promotional campaigns.

Overall, the residuals indicate that the model explains a substantial proportion of the variation in monthly sales, but there is still unexplained variation that could be addressed by including additional business variables in future analyses.
