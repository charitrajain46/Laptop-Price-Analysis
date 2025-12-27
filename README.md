# 💻 Laptop Price Analysis & Prediction

## 📌 Project Overview

The **Laptop Price Analysis** project focuses on analyzing laptop specifications and building a machine learning model to understand the factors that influence laptop prices. The project combines **Data Analysis, Exploratory Data Analysis (EDA), and Machine Learning** techniques to derive meaningful insights and predict laptop prices based on hardware and display features.

This project demonstrates a complete **data analyst workflow**, including data cleaning, visualization, feature analysis, and regression modeling.

---

## 🎯 Problem Statement

Laptop prices vary significantly depending on specifications such as brand, processor, RAM, storage, screen type, and graphics card.

The objective of this project is to:

* Analyze how different laptop features impact price
* Perform exploratory data analysis to identify trends and patterns
* Build a machine learning model to predict laptop prices

---

## 📂 Dataset Description

* **Source:** Kaggle (Laptop Prices Dataset)
* **Total Records:** 1,275
* **Total Features:** 23
* **Target Variable:** `Price_euros`

### Key Features:

* Company, Product, TypeName
* Screen Size (Inches), Screen Resolution
* RAM, Primary & Secondary Storage
* CPU Company, CPU Frequency, CPU Model
* GPU Company & Model
* Touchscreen, IPS Panel, Retina Display
* Operating System, Weight

The dataset was cleaned and checked for duplicates and missing values to ensure reliable analysis and modeling.

---

## 🛠️ Tools & Technologies Used

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **IDE / Environment:** Jupyter Notebook
* **Domain:** Data Analytics & Machine Learning

---

## 🔍 Project Workflow

### 1. Data Loading & Understanding

* Loaded the dataset using Pandas
* Checked data shape, data types, and null values

### 2. Data Cleaning

* Verified there were no missing values
* Ensured correct data formats

### 3. Exploratory Data Analysis (EDA)

* **Univariate Analysis:** Company, OS, RAM, Screen Type, Storage
* **Bivariate Analysis:** Price vs OS, RAM, Storage, CPU Frequency
* Visualizations using bar charts, pie charts, box plots, and scatter plots

### 4. Feature Engineering

* Converted categorical variables into numerical format
* Selected relevant features for modeling

### 5. Model Building

* Applied **Linear Regression**
* Split the dataset into training and testing sets

### 6. Model Evaluation

* Evaluated the model using:

  * Mean Squared Error (MSE)
  * R-Squared (R²)
* Visualized actual vs predicted prices

---

## 📊 Key Insights

* Laptops with **higher RAM and SSD storage** tend to have higher prices
* **Touchscreen, Retina Display, and IPS panels** significantly affect pricing
* macOS laptops are generally priced higher
* Storage type plays a major role in price variation

---

## ✅ Results

* Successfully built a regression model to predict laptop prices
* Extracted meaningful insights from laptop specifications
* Demonstrated an end-to-end data analysis and ML pipeline

---

## 🚀 Future Improvements

* Implement advanced models like **Random Forest** or **XGBoost**
* Perform feature scaling and hyperparameter tuning
* Deploy the model using Flask or Streamlit
* Build a real-time laptop price prediction web app

---

## 📁 Repository Structure

```
├── Laptop Price Analysis.ipynb   # Jupyter Notebook with analysis & model
├── laptop_prices.csv            # Dataset
├── Laptop Price Analysis _ ML _ FA _ DA Project.pdf  # Problem statement
├── README.md                    # Project documentation
```

---

## 👩‍💻 Author

**Charitra Jain**
MCA Student | Aspiring Data Analyst & Data Scientist

Python | SQL | EDA | Machine Learning

🔗 LinkedIn: https://www.linkedin.com/in/charitra-jain-8271b4240/

---

⭐ *If you find this project useful, feel free to star the repository!*
