

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
  - Daily monitoring of data drift using **Azure Monitor** and **Databricks**.
  - Automated retraining pipeline to maintain high accuracy over time.

---

## 🛠️ Technologies Used

- **Languages**: Python
- **Libraries**: Pandas, Scikit-learn, TensorFlow, MLflow, BeautifulSoup, Requests
- **Cloud Services**: Azure Data Lake, Azure Databricks, Azure ML, Azure Monitor, Azure Web Apps
- **MLOps Tools**: Azure DevOps, MLflow, Docker

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/laptop-fare-price-predictions.git
cd laptop-fare-price-predictions
```

### 2. Install Dependencies

This project uses `Poetry` for dependency management. Install Poetry and run:

```bash
poetry install
```

Or, if you use `pip`:

```bash
pip install -r requirements.txt
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory and set up your Azure, OpenAI, and other API credentials:

```bash
AZURE_STORAGE_CONNECTION_STRING=your_azure_connection_string
OPENAI_API_KEY=your_openai_api_key
```

### 4. Running the Project

To run the project and make predictions, use:

```bash
python app.py
```

---

## 🔍 Project Structure

```
├── data/                   # Raw and processed data files
├── notebooks/              # Jupyter notebooks for exploration and development
├── src/                    # Main source code for the model and data pipeline
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── prediction_service.py
│   └── ...
├── .env                    # Environment variables
├── pyproject.toml          # Project dependencies and configurations (Poetry)
├── Dockerfile              # Docker configuration
└── README.md               # Project documentation
```

---

## 🧠 Model Performance

- **Best Model**: XGBoost Regressor
- **Accuracy**: 92% (R2 Score)
- **Mean Absolute Error**: 120 USD

---

## 📈 Future Improvements

- Implement advanced model interpretability techniques (e.g., SHAP).
- Enhance feature engineering by incorporating user reviews and market trends.
- Expand to include more brands and regions for global price prediction.

---

## 🏆 Contributors

- **Babu Penosh Gorla** – Data Scientist, MLOps Expert
- **Brahmi Rathod** – ML Engineer
- **Harshavardhan Rimmanpudi** – Cloud Engineer

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact

For any queries, reach out via [email](mailto:penosh.gorla22@gmail.com).

---

## ⭐ Acknowledgements

A big thank you to the **Azure** team for providing excellent MLOps tools that made this project possible.

---

Feel free to customize this `README.md` based on your project specifics and repository details!
