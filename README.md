![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)

# Introduction
Supply chain analytics serves as a critical tool for organizations aiming to enhance the efficiency and effectiveness of their supply chain operations. By leveraging data-driven insights, supply chain analytics helps optimize operational processes, streamline workflows, and allocate 
resources efficiently. It plays a pivotal role in demand forecasting and inventory management, 
enabling organizations to predict market trends, reduce stockouts, and maintain optimal inventory 
levels. Additionally, supply chain analytics contributes to cost reduction by identifying areas for 
improvement in procurement, transportation, and overall supply chain costs.

![suppy chain](https://github.com/ManojKudkyal/Supply-chain-demand-forecasting/assets/119351017/f72d0bc0-3b27-4fc0-829e-8d87c3c55fb4)






# Objective of Project
The objective is to implement an advanced forecasting system that leverages predictive analytics, machine learning, and real-time data to provide accurate demand predictions, 
optimize inventory levels, and enhance overall supply chain resilience. 
Demand forecasting is essential for businesses to anticipate and plan for future customer 
demand accurately. By predicting consumer preferences and market trends, organizations can 
optimize inventory levels, streamline production processes, and enhance overall operational 
efficiency. This proactive approach minimizes the risk of stockouts or excess inventory, allowing 
businesses to meet customer needs efficiently

# Data Description
A Data Set of Supply Chains used by the company DataCo Global was used for the analysis. You can find the dataset in the "Data" folder.

# Project Workflow
The following is the systematic workflow of the project:

### 1. Data Collection: 
Gather historical sales data, inventory levels, and any relevant external data (e.g., economic indicators, promotional data).
Here we used the dataset from kaggle as mentioned above.

### 2. Feature Engineering: 
Relevant time-related features will be extracted from the date column, and additional features will be created.

### 3. Data Preprocessing: 
Clean and preprocess the raw data. This includes handling missing values, normalizing/standardizing data, and aggregating data as needed.

### 4. Exploratory Data Analysis (EDA): 
Perform EDA to understand the data distribution, detect patterns, and identify correlations. Visualization tools are used to aid in this analysis.

### 5. Model Training: 
Train various machine learning and statistical models using the preprocessed data and engineered features. Models could include time series models like ARIMA, SARIMA, Prophet and linear models like linear regression.

### 6. Model Evaluation: 
Evaluate the trained models using appropriate metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE) and Symmetric Mean Absolute Percentage Error(SMAPE). Select the best-performing model based on these evaluations.

### 7. Results Visualization: 
Generate and save visualizations to illustrate the model performance and predictions. This helps in communicating the results to stakeholders.


# Outputs of different models

## 1. Prophet
![prophet output](https://github.com/ManojKudkyal/Supply-chain-demand-forecasting/assets/119351017/a54094cf-3476-4edf-a31d-bcb2e81a6f1e)

## 2. Arima
![arima output](https://github.com/ManojKudkyal/Supply-chain-demand-forecasting/assets/119351017/55935272-dee1-4e41-85d5-a24ab23cae46)

## 3. SARIMA 
![sarima output](https://github.com/ManojKudkyal/Supply-chain-demand-forecasting/assets/119351017/ead36fb3-0e8c-47ba-b917-11d9a479149a)

## 4. Linear Regression
![linear output](https://github.com/ManojKudkyal/Supply-chain-demand-forecasting/assets/119351017/f1ae88fc-39c4-4c23-a71e-1e57f26facbf)

# Preformance Metrics
Performance metric of different model are evaluated and represented in the format of table below
![metrics](https://github.com/ManojKudkyal/Supply-chain-demand-forecasting/assets/119351017/1e5c7364-c1d8-40cc-8e6a-0097fee92a6c)
