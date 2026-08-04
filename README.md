# 🧠 Mansik Santulan Score
### Mental Health Prediction System using Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-API-green?style=for-the-badge&logo=fastapi)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</p>

---

# 📖 About the Project

**Mansik Santulan Score** is a Machine Learning based Mental Health Prediction System that predicts whether a student is at risk of depression based on academic, personal, and lifestyle-related factors.

The project performs complete data preprocessing, exploratory data analysis, feature engineering, machine learning model training, evaluation, and prediction through a FastAPI backend.

This project demonstrates the complete Machine Learning workflow from raw data to deployment-ready prediction API.

---

# 🎯 Objectives

- Predict students' mental health status using Machine Learning.
- Analyze the factors affecting mental health.
- Compare multiple ML algorithms.
- Build a reusable prediction model.
- Provide prediction through FastAPI.
- Create a scalable architecture for future deployment.

---

# ✨ Features

- 📊 Data Cleaning
- 📈 Exploratory Data Analysis
- 🧹 Missing Value Handling
- 🔄 Feature Engineering
- ⚙️ Feature Scaling
- 🤖 Machine Learning Model
- 📉 Model Evaluation
- 🚀 FastAPI REST API
- 📦 Saved Model (.pkl)
- 📑 Swagger API Documentation

---

# 🏗️ Project Architecture

```
                Dataset
                   │
                   ▼
          Data Preprocessing
                   │
                   ▼
      Exploratory Data Analysis
                   │
                   ▼
          Feature Engineering
                   │
                   ▼
        Machine Learning Model
                   │
                   ▼
           Model Evaluation
                   │
                   ▼
            Saved Model (.pkl)
                   │
                   ▼
              FastAPI Backend
                   │
                   ▼
         REST API Prediction
```

---

# 📂 Project Structure

```
mental-health-prediction/

│
├── static/
│
├── venv/
│
├── __pycache__/
│
├── ML_Project.ipynb
│
├── main.py
│
├── Mental_Health_Model.pkl
│
├── requirements.txt
│
├── README.md
│
└── Student Social Media And Mental Health.csv
```

---

# 📊 Dataset

The dataset contains information related to students and their mental health.

### Features

- Age
- Gender
- Academic Pressure
- Study Satisfaction
- Sleep Duration
- Dietary Habits
- Study Hours
- Financial Stress
- Family History
- Social Media Usage
- Academic Performance

### Target

- Depression Prediction

---

# 🔍 Data Preprocessing

The following preprocessing techniques were applied:

- Missing Value Handling
- Duplicate Removal
- Label Encoding
- Feature Scaling
- Data Cleaning
- Feature Selection

---

# 📈 Exploratory Data Analysis

EDA includes:

- Histograms
- Count Plots
- Boxplots
- Correlation Heatmap
- Feature Distribution
- Target Distribution

---

# 🤖 Machine Learning

Algorithms experimented with:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors
- Gradient Boosting

---

# 📏 Model Evaluation

Evaluation metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

---

# ⚡ API

The project uses **FastAPI** for serving predictions.

### Run Server

```bash
uvicorn main:app --reload
```

### Swagger Documentation

```
http://127.0.0.1:8000/docs
```

### ReDoc

```
http://127.0.0.1:8000/redoc
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/nakranimeet18/mental-health-prediction.git
```

## Go to Project

```bash
cd mental-health-prediction
```

## Create Virtual Environment

```bash
python -m venv venv
```

Activate

### Windows

```bash
venv\Scripts\activate
```

### Mac/Linux

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run FastAPI

```bash
uvicorn main:app --reload
```

---

# 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Processing |
| NumPy | Numerical Computing |
| Matplotlib | Visualization |
| Seaborn | Data Visualization |
| Scikit-Learn | Machine Learning |
| Joblib | Model Saving |
| FastAPI | REST API |
| Uvicorn | API Server |
| Jupyter Notebook | Model Development |
| Git | Version Control |
| GitHub | Repository Hosting |

---

# 📷 Screenshots

## Home Page

# 📌 Future Improvements

- Deep Learning Models
- Explainable AI (SHAP)
- Real-Time Dashboard
- User Authentication
- Cloud Deployment
- Docker Support
- Database Integration
- Mobile Application

---

# 📚 Requirements

```
Python 3.12+

FastAPI

Uvicorn

Scikit-Learn

Pandas

NumPy

Matplotlib

Seaborn

Joblib
```

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository

2. Create a feature branch

3. Commit your changes

4. Push the branch

5. Open a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

## Meet Nakrani

**B.Tech Information Technology**

Data Science | Machine Learning | AI | Python Developer

---

# 🔗 Links

### 💻 GitHub

https://github.com/nakranimeet18

### 💼 LinkedIn

https://www.linkedin.com/in/meet-nakrani-202092407/

### 📂 Repository

https://github.com/nakranimeet18/mental-health-prediction

### website link
https://mental-health-prediction-lu52.onrender.com

### 📧 Email

nakranimeet18@gamil.com

---

# ⭐ Support

If you found this project useful,

⭐ Star this repository.

🍴 Fork the repository.

📢 Share it with others.

---

<p align="center">

Made with ❤️ by <b>Meet Nakrani</b>

</p>
