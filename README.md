

# Laptop Fare Price Predictions 🖥️💸

Welcome to the **Laptop Fare Price Predictions** project! This repository contains the code and workflow of an MLOps project focused on predicting the prices of laptops based on various features like brand, specifications, and more. The project demonstrates the end-to-end pipeline of data collection, preprocessing, model building, deployment, and monitoring within an MLOps framework using Azure services.

---

## 🚀 Project Overview

The primary objective of this project is to build a machine learning model that can predict laptop prices accurately. It is fully integrated into an MLOps pipeline using **Azure** to automate key processes such as data ingestion, model training, deployment, and continuous monitoring.

---

## 🏗️ Key Features

- **Data Collection & Storage**: 
  - Data was collected from multiple sources using web scraping and APIs.
  - Stored securely in **Azure Data Lake** for scalability and availability.
  
- **Data Preprocessing**:
  - Used **Azure Data Flow** for cleaning, transforming, and preparing the data for modeling.
  
- **Model Training**:
  - Built and trained multiple models using **Azure Databricks**.
  - Managed experiments using **MLflow** for efficient tracking of hyperparameters and performance.
  
- **Model Deployment**:
  - Deployed the best-performing model using **Azure Web App Services** for real-time predictions.
  
- **Monitoring & Retraining**:
  - Daily monitoring of data drift using **Azure Dataflow** and **Databricks**.
  - Automated retraining pipeline to maintain high accuracy over time.

---

## 🛠️ Technologies Used

- **Languages**: Python
- **Libraries**: Pandas, Scikit-learn MLflow, BeautifulSoup, Requests
- **Cloud Services**: Azure Data Lake, Azure Databricks, Function Apps, Azure Datafloe, Azure Web Apps
- **MLOps Tools**: Azure DevOps, MLflow, Github
---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Penosh22/mlops_project.git
cd mlops_project
```

### 2. Install Dependencies

use `pip`:

```bash
pip install -r requirements.txt
```

---

## 🧠 Model Performance

- **Best Model**: XGBoost Regressor
- **MAPE**: 0.17

---

## 📈 Future Improvements

- Implement advanced model interpretability techniques (e.g., SHAP).
- Enhance feature engineering by incorporating user reviews and market trends.
- Expand to include more brands and regions for global price prediction.

---


## 📞 Contact

For any queries, reach out via [email](mailto:penosh.gorla22@gmail.com).

---

## ⭐ Acknowledgements

A big thank you to the **Azure** team for providing excellent MLOps tools that made this project possible.

---

Feel free to customize this `README.md` based on your project specifics and repository details!
