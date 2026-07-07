# 🔥 Algerian Forest Fire Prediction using Ridge Regression

An end-to-end Machine Learning project that predicts the **Fire Weather Index (FWI)** using the **Algerian Forest Fires Dataset**. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training with **Ridge Regression**, and deployment using **Flask**.

---

## 📌 Project Overview

The Algerian Forest Fires Dataset contains meteorological and fire weather observations collected from two regions in Algeria. This project aims to predict the **Fire Weather Index (FWI)**, an important indicator used to estimate fire intensity and risk.

The workflow includes:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Scaling
- Model Training
- Model Evaluation
- Web Application Deployment using Flask

---

## 📂 Project Structure

```
.
├── models/
│   ├── ridge.pkl
│   └── scaler.pkl
├── notebooks/
│   ├── Algerian_forest_fire_EDA.ipynb
│   ├── code.ipynb
│   └── modelTraining.ipynb
├── templates/
│   ├── home.html
│   └── index.html
├── application.py
├── requirements.txt
└── README.md
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Flask
- HTML5
- CSS3

---

## 📊 Dataset

**Dataset:** Algerian Forest Fires Dataset

The dataset contains weather-related features such as:

- Temperature
- Relative Humidity (RH)
- Wind Speed (Ws)
- Rain
- FFMC
- DMC
- DC
- ISI
- BUI

Target Variable:

- **FWI (Fire Weather Index)**

---

## 🤖 Machine Learning Model

The project uses **Ridge Regression**, a regularized linear regression algorithm that helps reduce overfitting by applying L2 regularization.

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Riddhi256/algerian-forest-fire-prediction.git
```

Navigate to the project folder

```bash
cd algerian-forest-fire-prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Flask application

```bash
python application.py
```

Open your browser and visit

```
http://127.0.0.1:5000/
```

---

## 📈 Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature Scaling
- Ridge Regression Model
- Real-time FWI prediction through a Flask web interface

---


## 📜 Future Improvements

- Deploy the application on Render or Railway
- Experiment with different regression algorithms
- Improve UI using Bootstrap
- Add model performance visualization



