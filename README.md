# Product Sales Prediction using Machine Learning

## Project Overview

This project aims to predict product sales based on item characteristics and outlet features. The goal is to help businesses understand the key factors that influence sales performance and build a model that can support data-driven decision-making.

---

## Key Insights from the Data

### 1. Distribution of Product Sales
<img width="571" height="455" alt="histo" src="https://github.com/user-attachments/assets/586d5fe5-4a77-4c95-9f16-07df3f786afe" />

Most products have low to moderate sales, while only a small number of products achieve very high sales. This indicates a right-skewed distribution and suggests that high-performing products are relatively rare.

---

### 2. Sales by Outlet Type
<img width="589" height="546" alt="box" src="https://github.com/user-attachments/assets/76e4fd0a-dfdc-49f9-b9ca-c74ea9aec661" />

Sales vary significantly by outlet type. Supermarket Type3 consistently shows higher sales, while Grocery Stores have the lowest. This highlights the strong impact of store type on sales performance.

---

## Model Summary

Several models were tested to predict product sales, including:

- Linear Regression
- Random Forest (Default)
- Random Forest (Tuned)

### Final Model: Tuned Random Forest Regressor

The tuned Random Forest model was selected as the best-performing model.

### Performance:

- **R² Score (Test):** 0.59  
- **Mean Absolute Error (MAE):** ~737  

### Interpretation:

- The model explains approximately **59% of the variation in sales**
- On average, predictions differ from actual sales by about **737 units**

---

## Why This Model?

- Linear Regression underfit the data and failed to capture complex relationships  
- Default Random Forest overfit the training data  
- Tuned Random Forest achieved the best balance between accuracy and generalization  

---

## Conclusion

Price and outlet type are the most influential factors affecting product sales. The final model provides a reasonable level of prediction accuracy and can be used to support business decisions related to pricing strategies and store performance.

---

## Next Steps

- Improve model performance by testing additional algorithms
- Perform feature engineering to capture more complex patterns
- Deploy the model in a real-world application for business use
