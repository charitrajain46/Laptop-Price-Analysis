##💻 Laptop Price Analysis & Prediction
#📌 Project Overview

The Laptop Price Analysis project focuses on analyzing laptop specifications and building a machine learning model to understand the factors that influence laptop prices. The project combines Data Analysis, Exploratory Data Analysis (EDA), and Machine Learning to derive insights and predict laptop prices based on hardware and display features.

This project is designed to demonstrate real-world data analyst and machine learning workflows, including data cleaning, visualization, and regression modeling.

#🎯 Problem Statement

Laptop prices vary significantly based on specifications such as brand, processor, RAM, storage, screen type, and graphics card.
The objective of this project is to:

Analyze how different laptop features impact price

Perform exploratory data analysis to identify trends and patterns

Build a regression model to predict laptop prices accurately

#📂 Dataset Description

Source: Kaggle (Laptop Prices Dataset)

Total Records: 1,275

Total Features: 23

Target Variable: Price_euros

Key Features:

Company, Product, TypeName

Screen Size (Inches), Screen Resolution

RAM, Storage (Primary & Secondary)

CPU Company, CPU Frequency, CPU Model

GPU Company & Model

Touchscreen, IPS Panel, Retina Display

Operating System, Weight

The dataset was preprocessed to remove duplicates and ensure consistency for machine learning.

#🛠️ Tools & Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

IDE / Environment: Jupyter Notebook

Domain: Data Analytics & Machine Learning

#🔍 Project Workflow

Data Loading & Understanding

Loaded dataset using Pandas

Checked shape, data types, and null values

Data Cleaning

Verified no missing values

Ensured correct data formats

Exploratory Data Analysis (EDA)

Univariate analysis (Company, OS, RAM, Screen, Storage)

Bivariate analysis (Price vs OS, RAM, Storage, CPU Frequency)

Visualizations using bar plots, pie charts, box plots, and scatter plots

Feature Engineering

Converted categorical variables into numerical format

Selected relevant features for modeling

Model Building

Applied Linear Regression

Split data into training and testing sets

Model Evaluation

Evaluated model using:

Mean Squared Error (MSE)

R-Squared (R²)

Compared actual vs predicted prices using visualization

#📊 Key Insights

Laptops with higher RAM, SSD storage, and better CPUs tend to have higher prices

Touchscreen, Retina Display, and IPS panels significantly impact pricing

macOS laptops are generally priced higher than other operating systems

Storage type plays a crucial role in pricing trends

#✅ Results

Successfully built a regression model to predict laptop prices

Gained actionable insights into feature-price relationships

Demonstrated end-to-end data analysis and ML pipeline

#🚀 Future Improvements

Try advanced models like Random Forest, XGBoost

Perform feature scaling and hyperparameter tuning

Deploy the model using Flask or Streamlit

Convert price predictions into real-time web application

#📁 Repository Structure
├── Laptop Price Analysis.ipynb   # Jupyter Notebook with full analysis & model
├── laptop_prices.csv            # Dataset
├── Project_Report.pdf           # Problem statement & documentation
├── README.md                    # Project description

#👩‍💻 Author

Charitra Jain
MCA Student | Aspiring Data Analyst
🔗 LinkedIn: https://www.linkedin.com/in/charitra-jain-8271b4240/
