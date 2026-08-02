# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview
This project predicts the selling price of used cars using Machine Learning. A Linear Regression model is trained on historical car data to estimate the selling price based on different vehicle features.

---

## 📂 Dataset
The dataset contains **301 records** and includes the following features:

- Car_Name
- Year
- Selling_Price (Target Variable)
- Present_Price
- Kms_Driven
- Fuel_Type
- Seller_Type
- Transmission
- Owner

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📊 Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset using Pandas.
- Displayed the first and last records.
- Generated descriptive statistics.
- Checked for missing values.
- Explored categorical variables using `value_counts()`.
- Applied Label Encoding on:
  - Fuel_Type
  - Seller_Type
  - Transmission

---

## 📈 Data Visualization

Visualizations created in this project include:

- Histogram of Selling Price Distribution
- Scatter Plot of Year vs Selling Price

These visualizations help understand the distribution of selling prices and the relationship between manufacturing year and selling price.

---

## 🤖 Model Building

Algorithm Used:

- Linear Regression

Steps:

1. Feature Selection
2. Train-Test Split (80% Training, 20% Testing)
3. Model Training
4. Prediction
5. Model Evaluation

---

## 📊 Model Performance

Evaluation Metrics:

- **Mean Absolute Error (MAE):** 1.2218
- **Mean Squared Error (MSE):** 3.5290
- **R² Score:** 0.8468

The model achieved an **R² Score of 84.68%**, indicating good prediction performance.

---

## 📁 Project Structure

```
DataScience-Task3-CarPricePrediction/
│── Task_3_car_price_prediction_Data_science.ipynb
│── cardata.csv
│── README.md
```

---

## 🚀 How to Run

1. Clone this repository.
2. Install the required libraries.
3. Open the Jupyter Notebook.
4. Run all cells sequentially.

Required libraries:

```
pip install pandas numpy matplotlib scikit-learn
```

---

## 📌 Conclusion

The Linear Regression model successfully predicts used car selling prices with good accuracy. The project demonstrates the complete Machine Learning workflow including data preprocessing, visualization, model training, prediction, and evaluation.

---

## 👨‍💻 Author

**Faizan Khan**

Oasis Infobyte Internship – Data Science

GitHub: https://github.com/faizanhub141
