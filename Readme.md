# Logistic Regression Model for Classification

This project implements a **Logistic Regression** model to classify data using **scikit-learn**.  
It includes a full **ML pipeline**, model training, evaluation, and saving the trained model for future use with **joblib**.

---

## 📌 Features
- Preprocessing with **Pipeline** (scaling + model).
- Logistic Regression classifier.
- Model evaluation (accuracy, confusion matrix, cross-validation).
- Save and load trained model using `joblib`.
- Easily extendable for deployment (API / Web App).

---

## ⚙️ Tech Stack
- Python 3.x
- Scikit-learn
- Pandas, NumPy
- Matplotlib / Seaborn (for visualization)
- Joblib

---

## 📂 Project Structure

```
├── data/ 
├── model/ 
├── index.ipynb # 
└── README.md # Project documentation

```

---

## 🚀 How to Run

### 1️⃣ Clone the repository

```
git clone https://github.com/Sidabd17/Fake-News-Detection.git
```
---

### 2️⃣ Install dependencies
```
pip install -r requirements.txt
```

---

## 🛠️ Usage of Saved Model

You can load the trained model in any future script:
```
import joblib

# Load model
pipeline = joblib.load("model/log_reg_pipeline.pkl")

# Predict on new data
y_pred = pipeline.predict(new_data)
```
---

## Author 
**Md Sajid**
