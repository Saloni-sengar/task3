# 🏠 Linear Regression: Predicting House Prices (California Housing Dataset)

This project is a simple demonstration of how to build, evaluate, and visualize a **Linear Regression** model using Python and `scikit-learn`. The model predicts house prices based on **median income** using the **California Housing dataset**.

---

## 🔧 Technologies Used

- Python 3
- scikit-learn
- pandas
- matplotlib
- numpy

---

## 📂 Project Overview

The following steps are covered in this project:

1. **Import & preprocess the dataset**
2. **Split the data into training and test sets**
3. **Train a Linear Regression model**
4. **Evaluate the model** using MAE, MSE, and R² score
5. **Visualize the regression line**
6. **Interpret the model coefficients**

---

## 📊 Dataset

We use the **California Housing dataset**, which contains information about various California districts including features like median income, average occupancy, and house age. In this project, we focus only on:

- **Feature**: `MedInc` – Median income in the district
- **Target**: `PRICE` – Median house value

---

## ▶️ How to Run

### 1. Install Required Libraries

```bash
pip install numpy pandas matplotlib scikit-learn
python linear_regression.py
📈 Output
Regression line plotted against actual data points

Console output showing:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R-squared Score (R²)

Intercept and Slope of the model

📘 Model Interpretation
Intercept (b₀): Predicted base price when income is zero.

Slope (b₁): For each unit increase in median income, house price increases by approximately this much.

R² Score: Indicates the percentage of variance in house prices explained by median income.

📎 Example Plot
The red line represents predicted values by the Linear Regression model, while the blue points represent actual house prices.

👤 Author
Project created by ChatGPT (OpenAI) for demonstration and learning purposes. You can extend this project by:

Using multiple features

Trying other models (Ridge, Lasso, etc.)

Using a custom dataset

📝 License
This project is open-source and free to use for educational purpose

---



