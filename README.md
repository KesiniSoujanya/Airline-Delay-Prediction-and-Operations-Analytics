# Airline-Delay-Prediction-and-Operations-Analytics
✈ Airline Delay Prediction & Operations Analytics
📌 Project Overview

Airline delays significantly affect airline operations and passenger satisfaction.
This project uses machine learning techniques and operational analytics to predict flight delays and analyze delay patterns across airlines and routes.

The system processes historical flight data, applies data preprocessing, feature engineering, and multiple ML strategies, and generates predictive insights along with analytical visualizations.

🎯 Project Objectives

Predict whether a flight will be delayed or on-time

Handle class imbalance using SMOTE and RSMOTE

Compare different machine learning strategies

Store processed data and predictions using MySQL database

Generate operational analytics visualizations

📊 Dataset

The dataset contains 100,000 airline flight records used for delay prediction analysis.

📥 Download Dataset from Kaggle:

https://www.kaggle.com/datasets/YOUR_USERNAME/airline-flight-delay-dataset

Dataset features include:

Feature	Description
OP_CARRIER	Airline carrier code
ORIGIN	Origin airport
DEST	Destination airport
CRS_DEP_TIME	Scheduled departure time
DISTANCE	Flight distance
DEP_DELAY	Departure delay in minutes
DELAY	Target variable (1 = Delayed, 0 = On-Time)
⚙️ Machine Learning Models

The following strategies were implemented:

SMOTE + Random Forest

RSMOTE + Random Forest

XGBoost

GridSearch XGBoost

🏆 Best Model Performance
Metric	Value
Model	XGBoost
Accuracy	92.98%
F1 Score	78.54%
ROC-AUC	0.93

XGBoost achieved the best predictive performance among all models.

📈 Visualizations

The project includes multiple analytical visualizations:

Confusion Matrix

ROC Curve

Airline Delay Rate Analysis

Flight Route Delay Heatmap

Model Strategy Comparison

Flight Route Delay Network Graph

These visualizations help analyze airline delay patterns and operational insights.

🗄 SQL Database Integration

The project integrates MySQL database storage for managing flight data and predictions.

Technologies used:

MySQL

SQLAlchemy

PyMySQL

SQL queries are available in:

sql/queries.sql
🛠 Technologies Used
Category	Tools
Programming	Python
Data Processing	Pandas, NumPy
Machine Learning	Scikit-learn, XGBoost
Imbalanced Learning	SMOTE, RSMOTE
Visualization	Matplotlib, Seaborn
Network Analysis	NetworkX
Database	MySQL
Development	Jupyter Notebook
📂 Project Structure
airline-delay-prediction/
│
├── dataset/
│   └── flights.zip
│
├── notebooks/
│   └── airline_delay_prediction.ipynb
│
├── sql/
│   └── queries.sql
│
├── images/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── heatmap.png
│
├── requirements.txt
├── README.md
🚀 Installation

Clone the repository:

git clone https://github.com/YOUR_USERNAME/airline-delay-prediction.git

Install dependencies:

pip install -r requirements.txt

Run the notebook:

jupyter notebook
📚 Base Research Paper

Chakrabarty, N.
"A Data Mining Approach to Flight Arrival Delay Prediction"
IEEE, 2019.

👨‍💻 Author

Souji
B.Tech Final Year Project
Airline Delay Prediction & Operations Analytics
