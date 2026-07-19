# Airline-Passenger-Satisfaction
This is my classification based AI/ML Project which will include working on the Airline Passenger Satisfaction dataset 


# ✈️ Airline Passenger Satisfaction Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting **airline passenger satisfaction** using various supervised machine learning classification algorithms. The objective is to identify the factors that influence passenger satisfaction and develop predictive models that can help airlines improve customer experience and make data-driven business decisions.

The project includes complete data preprocessing, exploratory data analysis (EDA), feature engineering, feature selection, model building, hyperparameter tuning, and model evaluation.

---

## 🎯 Problem Statement

Passenger satisfaction is one of the key performance indicators for the airline industry. Airlines collect customer feedback regarding travel experience, service quality, delays, comfort, and onboard facilities.

The objective of this project is to build machine learning models capable of predicting whether a passenger is:

- Satisfied
- Neutral or Dissatisfied

based on various flight and service-related attributes.

---

## 📂 Dataset Information

- **Dataset Name:** Airline Passenger Satisfaction Dataset
- **Task:** Binary Classification
- **Target Variable:** `satisfaction`

### Dataset Features

The dataset contains passenger-related information including:

- Gender
- Customer Type
- Age
- Type of Travel
- Class
- Flight Distance
- Inflight WiFi Service
- Seat Comfort
- Food and Drink
- Online Boarding
- Cleanliness
- Baggage Handling
- Check-in Service
- Departure Delay
- Arrival Delay
- Many other service-related ratings

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📚 Machine Learning Algorithms Implemented

The following classification models were implemented and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. K-Nearest Neighbors (KNN)
5. Gaussian Naive Bayes
6. Support Vector Machine (SVM)

---

## ⚙ Data Preprocessing

The following preprocessing techniques were applied:

- Missing Value Handling
- Duplicate Record Checking
- Outlier Detection using IQR
- Label Encoding
- Feature Engineering
- Feature Scaling using StandardScaler
- Train-Test Split (80:20)

---

## 🔧 Feature Engineering

New features were created to improve model performance.

### Total Delay

```
Total Delay = Departure Delay + Arrival Delay
```

### Overall Service Rating

Average of multiple passenger service ratings including:

- WiFi Service
- Seat Comfort
- Online Boarding
- Food & Drink
- Inflight Entertainment
- Cleanliness
- Baggage Handling
- Check-in Service
- On-board Service

---

## 📊 Exploratory Data Analysis (EDA)

More than **20 visualizations** were created to understand the dataset.

Some important visualizations include:

- Passenger Satisfaction Distribution
- Gender Distribution
- Customer Type
- Travel Type
- Passenger Class
- Age Distribution
- Flight Distance Distribution
- Delay Analysis
- Satisfaction vs Gender
- Satisfaction vs Class
- Satisfaction vs Travel Type
- Satisfaction vs Customer Type
- Correlation Heatmap
- Pair Plot
- Feature Importance

Each visualization includes:

- Why the chart was selected
- Key insights
- Business impact

---

## 📈 Model Evaluation Metrics

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report
- Cross Validation

---

## 🔍 Hyperparameter Tuning

GridSearchCV was used for optimizing all classification models.

The tuning process improved:

- Model Accuracy
- Precision
- Recall
- F1 Score
- Generalization Performance

---

## 📊 Business Insights

The analysis revealed that the following factors significantly influence passenger satisfaction:

- Online Boarding
- Seat Comfort
- Inflight WiFi Service
- Overall Service Rating
- Flight Class
- Cleanliness
- Flight Distance
- Total Delay
- On-board Service
- Inflight Entertainment

These insights can help airlines improve customer experience and increase passenger retention.

---

## 📁 Project Structure

```
Airline-Passenger-Satisfaction/
│
├── Airline_Passenger_Satisfaction.ipynb
├── Airline_Passenger_Satisfaction.py
├── train.csv
├── README.md
└── requirements.txt
```

---

## ▶ How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/Airline-Passenger-Satisfaction.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run the Notebook

```bash
jupyter notebook Airline_Passenger_Satisfaction.ipynb
```

---

## 📊 Results

The machine learning models successfully predicted passenger satisfaction with high accuracy.

Among all implemented models:

- Random Forest achieved the best overall performance.
- Support Vector Machine also produced excellent classification results.
- Logistic Regression provided a strong baseline model.
- Decision Tree offered high interpretability.
- KNN performed well after feature scaling.
- Gaussian Naive Bayes provided fast and efficient predictions.

---

## 💼 Business Impact

This project enables airlines to:

- Predict passenger satisfaction before receiving feedback.
- Improve customer experience through data-driven decisions.
- Reduce customer churn.
- Enhance loyalty programs.
- Optimize onboard services.
- Improve delay management.
- Increase customer retention and revenue.

---

## 🚀 Future Enhancements

Future improvements may include:

- XGBoost Classifier
- LightGBM
- CatBoost
- Deep Learning Models
- Model Deployment using Streamlit
- Real-time Passenger Satisfaction Prediction
- Explainable AI using SHAP and LIME

---

## 📖 Conclusion

This project demonstrates the successful application of machine learning techniques for predicting airline passenger satisfaction. Through comprehensive data preprocessing, exploratory data analysis, feature engineering, and model evaluation, valuable insights were obtained regarding the factors influencing customer satisfaction.

The Random Forest Classifier achieved the best predictive performance, while feature importance analysis identified service quality, seating comfort, online boarding, cleanliness, WiFi service, and delays as the primary contributors to passenger satisfaction.

The developed models can assist airlines in making proactive, data-driven decisions that improve customer experience, increase passenger loyalty, reduce complaints, and support strategic business planning.

---

## 👨‍💻 Author

**Yuvaraju Mogatala**

B.Tech – Electronics and Communication Engineering

Guru Gobind Singh Indraprastha University

---

## ⭐ If you found this project helpful, consider giving it a star!
