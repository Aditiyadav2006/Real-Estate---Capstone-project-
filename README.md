# Real Estate Price Prediction and Analysis Capstone Project

---

## 💡 Project Overview

This capstone project applies a combination of **Exploratory Data Analysis (EDA)** and **Machine Learning** to a real estate dataset (likely featuring housing characteristics and prices, such as the famous Boston Housing dataset).

The core objectives are to:
1.  **Analyze** the impact of various socioeconomic and neighborhood factors (e.g., crime rate, proximity to employment centers, pollution) on housing values.
2.  **Clean and preprocess** the raw data, handling outliers and standardizing features.
3.  **Develop Predictive Models** using both **Regression** (to predict continuous house prices) and **Classification** (to categorize houses based on value or other target features).

## 📊 Analysis & Methodology

The project is structured into two main Jupyter notebooks, outlining a complete data science workflow:

### 1. Exploratory Data Analysis (EDA) & Data Preprocessing (`real_estate_EDA.ipynb`)
* **Data Cleaning:** Addressing missing values and identifying and handling outliers for key features.
* **Feature Engineering:** Creating new, meaningful variables like **Property Age** from existing data, and potentially a **Price per Sqft** or a categorical price bin.
* **Visualization:** Using histograms, scatter plots, and correlation matrices to understand feature distributions, relationships between variables, and the linearity of the target variable (**MEDV** - Median Value).
* **Preprocessing:** Applying techniques like **log transformations** to normalize skewed variables and preparing the cleaned data (`real_estate_cleaned.csv`) for modeling.

### 2. Machine Learning Modeling (`real_estate_CP.ipynb`)
This notebook covers both Regression (predicting price) and Classification (categorizing data):
* **Regression Modeling (Price Prediction):** Implementing and evaluating models like **Support Vector Regression (SVR)** to predict the continuous price variable, assessed using metrics like **R² Score**, **MAE** (Mean Absolute Error), and **RMSE** (Root Mean Squared Error).
* **Classification Modeling (Categorical Outcome):** Training classification models (e.g., **SVM, Naive Bayes, Decision Trees, Random Forests**) on a modified target variable, evaluated using **Accuracy** and **Confusion Matrices**.

## 📁 Repository Structure

| File Name | Description |
| :--- | :--- |
| `data.csv` | The raw, initial dataset used for the project's analysis. |
| `real_estate_cleaned.csv` | The clean, preprocessed, and feature-engineered dataset ready for direct modeling. |
| `real_estate_EDA.ipynb` | Jupyter Notebook detailing the entire Exploratory Data Analysis, data cleaning, transformation, and visualization process. |
| `real_estate_CP.ipynb` | Jupyter Notebook containing the implementation, training, and evaluation of both the Regression and Classification Machine Learning models. |

## 🛠️ Technologies & Libraries

This project was built using **Python** and standard data science libraries:

* **Data Manipulation**: `pandas`, `numpy`
* **Visualization**: `matplotlib`, `seaborn`
* **Machine Learning**: `scikit-learn` (for SVR, SVC, Naive Bayes, Decision Trees, Random Forests, metrics, and preprocessing tools)
* **Environment**: `VS code`


You can also view the notebook directly on GitHub or platforms like **Google Colab** without needing a local setup.

***

## 👩‍💻 Author
**Aditi K**  
CSE (AI & ML) | Real Estate | Capstone project
