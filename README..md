# 🌍 Human Development Index (HDI) Prediction System using Machine Learning

::: {align="center"}
# 🌍 Human Development Index Prediction System

### End-to-End Machine Learning Web Application using Flask & Scikit-Learn

Predict the **Human Development Index (HDI)** of countries using
socio-economic indicators through an interactive web application powered
by Machine Learning.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?style=for-the-badge&logo=flask)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**End-to-End Machine Learning • Flask • Data Analysis • Deployment**
:::

------------------------------------------------------------------------

# 📑 Table of Contents

-   Overview
-   Project Highlights
-   Problem Statement
-   Objectives
-   Proposed Solution
-   Features
-   Technology Stack
-   System Architecture
-   Machine Learning Pipeline
-   Dataset
-   Exploratory Data Analysis
-   Data Preprocessing
-   Feature Engineering
-   Machine Learning Model
-   Model Evaluation
-   Project Structure
-   Flask Web Application
-   Installation
-   Prediction Workflow
-   Applications
-   Future Enhancements
-   Contributing
-   License

------------------------------------------------------------------------

# 📖 Overview

The **Human Development Index (HDI) Prediction System** is an end-to-end
Machine Learning application that predicts the Human Development Index
score of countries using socio-economic indicators. The project
demonstrates the complete ML lifecycle, including data preprocessing,
exploratory data analysis, feature engineering, model training,
evaluation, serialization, deployment, and prediction through a Flask
web application.

------------------------------------------------------------------------

# 🚀 Project Highlights

-   End-to-End Machine Learning Project
-   Exploratory Data Analysis (EDA)
-   Data Cleaning & Preprocessing
-   Feature Engineering
-   Linear Regression Model
-   Flask-Based Web Application
-   Real-Time HDI Prediction
-   Pickle Model Serialization
-   Clean Project Structure

------------------------------------------------------------------------

# 🎯 Problem Statement

The Human Development Index (HDI) measures the development level of
countries using health, education, and income indicators. Manual
analysis is time-consuming and difficult to scale. This project
automates HDI prediction using Machine Learning.

------------------------------------------------------------------------

# 🎯 Objectives

-   Predict HDI scores using ML.
-   Analyze socio-economic indicators.
-   Build a preprocessing pipeline.
-   Deploy the model using Flask.
-   Provide instant predictions.

------------------------------------------------------------------------

# ✨ Features

## 📊 Data Analysis

-   Dataset Exploration
-   Statistical Summary
-   Missing Value Detection
-   Correlation Analysis
-   Feature Relationship Analysis

## 📈 Data Visualization

-   Heatmaps
-   Scatter Plots
-   Distribution Plots
-   Histograms
-   Box Plots

## 🤖 Machine Learning

-   Linear Regression
-   Train-Test Split
-   Model Training
-   Model Evaluation
-   HDI Prediction

## 🌐 Flask Application

-   Interactive Interface
-   Input Validation
-   Responsive Design
-   Real-Time Prediction

------------------------------------------------------------------------

# 🛠 Technology Stack

  Category              Technology
  --------------------- ---------------------
  Language              Python 3.10+
  Machine Learning      Scikit-Learn
  Backend               Flask
  Frontend              HTML5, CSS3
  Data Analysis         Pandas
  Numerical Computing   NumPy
  Visualization         Matplotlib, Seaborn
  Model Storage         Pickle
  IDE                   Visual Studio Code

------------------------------------------------------------------------

# 🏗 System Architecture

``` mermaid
flowchart TD
A[User] --> B[Flask Web Application]
B --> C[Input Validation]
C --> D[Feature Engineering]
D --> E[Linear Regression Model]
E --> F[HDI Score Prediction]
F --> G[HDI Category Classification]
G --> H[Display Results]
```

# 🔄 Machine Learning Pipeline

``` mermaid
flowchart TD
A[Dataset] --> B[EDA]
B --> C[Data Cleaning]
C --> D[Missing Value Handling]
D --> E[Feature Engineering]
E --> F[Feature Selection]
F --> G[Train-Test Split]
G --> H[Model Training]
H --> I[Evaluation]
I --> J[HDI.pkl]
J --> K[Flask Deployment]
```

# 📂 Dataset

  Property       Value
  -------------- -----------
  Dataset Type   CSV
  Countries      195
  Features       82
  Target         HDI Score

Important Features:

-   Country
-   Life Expectancy
-   Mean Years of Schooling
-   Expected Years of Schooling
-   Gross National Income Per Capita
-   Internet Users

------------------------------------------------------------------------

# 📊 Exploratory Data Analysis

EDA includes:

-   Dataset Inspection
-   Statistical Summary
-   Correlation Matrix
-   Heatmaps
-   Scatter Plots
-   Distribution Analysis
-   Outlier Detection

------------------------------------------------------------------------

# ⚙ Data Preprocessing

-   Missing Value Handling
-   Data Cleaning
-   Feature Selection
-   Train-Test Split
-   Data Transformation

------------------------------------------------------------------------

# 🧠 Feature Engineering

The project selects relevant socio-economic indicators, removes
unnecessary attributes, and prepares feature vectors for prediction.

------------------------------------------------------------------------

# 🤖 Machine Learning Model

**Algorithm:** Linear Regression

The model learns relationships between socio-economic indicators and HDI
score, producing continuous predictions.

------------------------------------------------------------------------

# 📈 Model Evaluation

Evaluation Metrics:

-   R² Score
-   MAE
-   MSE
-   RMSE
-   Actual vs Predicted Analysis

------------------------------------------------------------------------

# 💾 Model Serialization

The trained model is saved as:

``` text
HDI.pkl
```

------------------------------------------------------------------------

# 🌐 Flask Web Application

The application contains:

-   Home Page
-   Prediction Page
-   Results Page

Users provide development indicators and receive predicted HDI scores
with categories.

------------------------------------------------------------------------

# 📂 Project Structure

``` text
Human-Development-Index/
├── Dataset/
├── Training/
├── Flask/
│   ├── templates/
│   ├── static/
│   ├── app.py
│   └── HDI.pkl
├── README.md
└── requirements.txt
```

------------------------------------------------------------------------

# 🚀 Installation

``` bash
git clone https://github.com/yourusername/Human-Development-Index.git
cd Human-Development-Index
pip install -r requirements.txt
python app.py
```

Visit:

``` text
http://127.0.0.1:5000
```

------------------------------------------------------------------------

# 🔄 Prediction Workflow

``` mermaid
flowchart TD
A[User Input] --> B[Validation]
B --> C[Feature Vector]
C --> D[Load Model]
D --> E[Predict HDI]
E --> F[Classify Category]
F --> G[Display Result]
```

------------------------------------------------------------------------

# 🌍 Applications

-   Government Policy Planning
-   Educational Research
-   Economic Analysis
-   Sustainable Development
-   AI Decision Support

------------------------------------------------------------------------

# 🚀 Future Enhancements

-   Random Forest
-   XGBoost
-   Explainable AI (SHAP/LIME)
-   REST API
-   React Frontend
-   Docker
-   Cloud Deployment
-   Dashboard Analytics

------------------------------------------------------------------------

# 🤝 Contributing

1.  Fork the repository.
2.  Create a feature branch.
3.  Commit changes.
4.  Push the branch.
5.  Open a Pull Request.

------------------------------------------------------------------------

# 📄 License

Released under the MIT License.

------------------------------------------------------------------------

::: {align="center"}
### ⭐ If you found this project useful, please consider giving it a star!
:::
