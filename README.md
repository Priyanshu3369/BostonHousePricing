# 🏠 Boston House Price Prediction

This is a simple machine learning web application that predicts Boston house prices based on various input features. The app is built using **Flask** and deployed using **Render**.

---

## 📌 Features

- Predicts house prices using a trained Linear Regression model.
- Takes user input through a web form.
- Displays predicted price on submission.
- Clean and responsive HTML interface.
- Hosted online using Render.

---

## 🚀 Live Demo

🔗 [Live Demo](https://bostonhousepricing-phwy.onrender.com)

---

## 🛠 Tech Stack

- **Python**
- **Flask**
- **scikit-learn**
- **HTML/CSS**
- **Render**

---

## 🔧 How It Works

1. The trained model (`model.pkl`) is loaded using `joblib`.
2. User inputs required features in a form (e.g., CRIM, RM, AGE, etc.).
3. Form data is passed to the backend Flask app.
4. The model predicts the price and returns it to the user on a new page.

---

## 🧪 Model Details

- Dataset: Boston Housing Dataset
- Model: Linear Regression
- Libraries: scikit-learn, pandas, numpy

---

## 🖥️ Installation (Local Setup)

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/BostonHousePricing.git
   cd BostonHousePricing
