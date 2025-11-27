# 🏥 Linear Regression Health Costs Calculator

This project is part of the FreeCodeCamp Machine Learning with Python Certification.

It predicts **healthcare costs** for individuals using **Linear Regression**. The model is trained on a dataset containing information such as age, sex, BMI, number of children, smoking habits, and region.

## Features
- Converts categorical variables to numeric values.
- Splits the dataset: 80% training, 20% testing.
- Uses `LinearRegression` from scikit-learn.
- Evaluates the model using **Mean Absolute Error (MAE)**.
- Predicts healthcare expenses for unseen test data.
- Plots predicted vs actual expenses for visualization.

## How to Run
1. Open `health_costs_calculator.ipynb` in **Google Colab**.  
2. Run all cells sequentially.  
3. The final cell tests the model on unseen data and plots predictions.  
4. Ensure the **MAE < 3500** to pass FCC requirements.  

## Project Structure

```
linear-regression-health-costs/
│
├── README.md
└── health_costs_calculator.ipynb
```

## Technologies Used
- Python  
- Pandas  
- NumPy  
- scikit-learn  
- Matplotlib / Seaborn  
- Google Colab  
