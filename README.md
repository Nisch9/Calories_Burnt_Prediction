# 🔥 Anticipating Caloric Expenditure with Machine Learning

An end-to-end machine learning project that predicts **calories burned during physical activity** using biometric and exercise data. The system covers the full ML lifecycle—from data preprocessing and model training to deployment via a Streamlit web application.

---

## 📌 Project Objective

The goal of this project is to build a predictive model that estimates calories burned based on user inputs such as age, gender, exercise duration, and physiological signals. This enables personalized fitness insights and demonstrates applied machine learning capabilities.

---

## 🚀 Features

* End-to-end ML pipeline
* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Multiple regression models
* Best-model selection
* Streamlit web app for real-time prediction
* Model serialization and deployment

---

## 🧠 Models Implemented

The following regression algorithms were evaluated:

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

**Best Performing Model:** XGBoost Regressor

* Accuracy ≈ 99%
* Mean Absolute Error ≈ 1.68

---

## 📂 Project Structure

```
Calories_Burnt/
│
├── Dataset/
│   ├── calories.csv
│   └── exercise.csv
│
├── Training/
│   └── Training.ipynb
│
├── Model/
│   └── model.pkl
│
├── web.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone <your-repo-url>
cd Calories_Burnt
```

---

### 2️⃣ Create Virtual Environment (Recommended)

**macOS / Linux**

```bash
python -m venv venv
source venv/bin/activate
```

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If Streamlit is missing:

```bash
pip install streamlit
```

---

## 📊 Model Training (Optional)

To retrain the model:

```bash
jupyter notebook Training/Training.ipynb
```

This notebook performs:

* Data loading
* Data preprocessing
* Feature engineering
* Model training
* Model evaluation
* Model saving

---

## 🌐 Run the Streamlit App

From the project root:

```bash
streamlit run web.py
```

Then open the local URL shown in the terminal (typically `http://localhost:8501`).

---

## 🖥️ Application Workflow

1. User enters biometric and exercise data
2. Model processes the input
3. Predicted calories burned is displayed in real time

---

## 📈 Evaluation Metrics

Models are evaluated using:

* R² Score
* Mean Absolute Error (MAE)

---

## 💡 Use Cases

* Personalized fitness guidance
* Workout optimization
* Weight management support
* Health analytics applications
* Wearable device integration (future scope)

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib / Seaborn
* Streamlit
