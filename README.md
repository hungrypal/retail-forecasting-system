# 🛒 Retail Sales Forecasting and Business Analytics

## 📌 Overview

Retail businesses generate massive amounts of sales data every day. Analyzing this data and accurately forecasting future sales helps organizations optimize inventory management, improve business planning, and make data-driven decisions.

This project is an end-to-end **Retail Sales Forecasting and Analytics** application built using **Python, Machine Learning, PostgreSQL, and Streamlit**. It combines data preprocessing, exploratory data analysis, feature engineering, machine learning model development, database integration, and an interactive dashboard into a single application.

The application allows users to analyze historical sales trends, explore business insights through interactive visualizations, and generate weekly sales predictions using a trained machine learning model.

---

# 🚀 Project Objectives

* Clean and preprocess retail sales data.
* Perform Exploratory Data Analysis (EDA).
* Engineer meaningful features for improved prediction.
* Train and evaluate multiple regression models.
* Select the best-performing model.
* Store processed data in PostgreSQL.
* Build an interactive Streamlit dashboard.
* Predict future weekly sales based on user inputs.

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* PostgreSQL
* Psycopg2-binary
* Streamlit
* Plotly
* Matplotlib
* Seaborn
* Pickle

---

# 📂 Project Structure

```
Retail-Sales-Forecasting/
│
├── app.py
├── requirements.txt
├── models/
│   └── random_forest.pkl
├── dataset/
├── notebooks/
├── sql/
├── images/
└── README.md
```

---

# 📊 Dataset

The dataset contains historical retail sales information including:

* Store ID
* Department
* Date
* Weekly Sales (Target Variable)
* Holiday Flag
* Store Type
* Store Size
* Temperature
* Fuel Price
* Consumer Price Index (CPI)
* Unemployment Rate
* MarkDown Features

---

# 🔄 Data Preprocessing

The preprocessing pipeline includes:

* Handling missing values
* Data type conversion
* Feature encoding
* Date feature extraction
* Outlier inspection
* Feature engineering
* Correlation analysis
* Dataset preparation for machine learning

---

# 📈 Exploratory Data Analysis

Interactive visualizations were created to understand business performance.

The dashboard provides insights such as:

* Sales trends over time
* Top performing stores
* Top performing departments
* Holiday vs Non-Holiday sales
* Feature-wise comparisons
* Store performance analysis
* Department performance analysis
* Distribution of important variables

---

# 🤖 Machine Learning

Several regression algorithms were trained and compared.

Models evaluated include:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Extra Trees Regressor
* XGBoost Regressor

Performance was evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

The best-performing model was saved using Pickle and integrated into the Streamlit application for real-time prediction.

---

# 🗄️ PostgreSQL Integration

The processed retail dataset is stored inside PostgreSQL.

Database integration enables:

* Efficient data storage
* SQL-based analysis
* Fast retrieval for dashboard visualizations
* Better scalability compared to CSV files

---

# 💻 Streamlit Dashboard Features

### 📌 Dashboard

* Interactive analytics
* KPI cards
* Sales overview

### 📊 Sales Analysis

* Weekly sales trends
* Monthly analysis
* Store-wise performance
* Department-wise performance

### 🏪 Top Performers

* Top Stores
* Top Departments

### 📉 Feature Analysis

Analyze the impact of:

* Store Type
* Store Size
* Holiday
* Temperature
* Fuel Price
* CPI
* Unemployment
* MarkDown values

### 🔍 Comparison

Compare:

* Stores
* Departments
* Weekly performance
* Historical trends

### 🎯 Sales Prediction

Users can enter:

* Store
* Department
* Date
* Holiday Flag
* Temperature
* Fuel Price
* CPI
* Unemployment
* MarkDown values

The trained machine learning model predicts the expected weekly sales instantly.

---

# 📦 Installation

Clone the repository

```bash
git clone <your-github-repository-link>
```

Move into the project directory

```bash
cd Retail-Sales-Forecasting
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

# 📷 Application Highlights

* Interactive Dashboard
* Business Intelligence Visualizations
* Machine Learning Forecasting
* PostgreSQL Database Integration
* Real-Time Sales Prediction

---

# 🎯 Future Improvements

* Deploy on Streamlit Community Cloud
* Add user authentication
* Connect to live retail databases
* Implement time-series forecasting models (ARIMA, Prophet, LSTM)
* Add inventory demand forecasting
* Build sales recommendation features

---

# 📜 License

This project is intended for educational and portfolio purposes.

---

# 👨‍💻 Author

**Rohit Jangid**

Aspiring Data Analyst | Machine Learning Enthusiast

### Connect with me

* LinkedIn: linkedin.com/in/rohitkrjangid-ml
* GitHub: https://github.com/hungrypal/retail-forecasting-system
* Email: (rohitk160204@gmail.com)
