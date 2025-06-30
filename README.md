# 🏠 House Price Predictor using Linear Regression

This project demonstrates how to use **Linear Regression** to predict house prices based on house sizes.  
It includes two implementations:
- ✅ **Manual implementation (from scratch)** using only NumPy
- ✅ **Scikit-learn implementation** for quick comparison

> 📍 Problem Statement:  
> Predict the price of a house based on its size (in square feet) using historical data.

---

## 🔗 Google Colab
[![Open in Colab](https://colab.research.google.com/drive/1x4_x3xW7tESXsjbhyBnQjSE6gTQjzjUl?usp=sharing)

---

## 📊 Dataset

The dataset used is synthetic/simple:
- `X` = House sizes in square feet
- `y` = Corresponding house prices

You can expand this later with CSV import or real datasets like from Kaggle or UCI.

---

## 🧠 What’s Inside

### 1️⃣ From Scratch (Manual) Implementation
- Implemented gradient descent manually
- Calculated cost (MSE), slope, and intercept
- Visualized convergence over iterations

### 2️⃣ Scikit-learn Implementation
- Used `LinearRegression` from `sklearn`
- Compared predictions and performance with manual method

---

## 📈 Sample Output

- Visual graphs of line fitting to data
- Loss curve showing cost function minimization
- Printout of learned slope (`m`) and intercept (`b`)
- Side-by-side comparison of both methods

---

## 🚀 How to Use

1. Open the Colab notebook
2. Run cells one-by-one
3. Modify or input your own house size to see predicted price

---

## 🛠️ Tech Used

- Python 🐍
- NumPy
- Matplotlib
- Scikit-learn (for Method 2)
- Google Colab

---

## 📌 Future Enhancements

- Add multiple features (e.g., number of bedrooms, location)
- Use real-world datasets
- Include polynomial regression



