# Flight-Fare-Prediction

Machine Learning project for predicting airline ticket prices using historical flight booking data. This project covers complete data preprocessing, exploratory data analysis (EDA), feature engineering, regression model training, and model evaluation to accurately estimate flight fares.

# ✈️ Flight Fare Prediction using Machine Learning

## 📌 Project Overview

Flight ticket prices fluctuate based on multiple factors such as airline, source city, destination, journey date, departure time, arrival time, duration, and number of stops. This project aims to develop a Machine Learning regression model capable of predicting flight ticket prices using historical flight data.

The project follows a complete Data Science workflow including data cleaning, preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison of multiple regression algorithms.

---

## 🎯 Objectives

- Perform comprehensive Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Handle missing values and duplicate records
- Extract useful date and time features
- Encode categorical variables
- Train multiple regression models
- Compare model performance
- Select the best model for flight fare prediction

---

## 📂 Dataset Information

The dataset contains historical flight booking information.

### Features

- Airline
- Date of Journey
- Source
- Destination
- Route
- Dep Time
- Arrival Time
- Duration
- Total Stops
- Additional Information
- Price (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

The project includes:

- Dataset overview
- Missing value analysis
- Duplicate value detection
- Statistical summary
- Airline-wise analysis
- Source and destination analysis
- Journey date analysis
- Price distribution
- Correlation analysis
- Outlier detection
- Data visualization

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Removing missing values
- Removing duplicate records
- Date feature extraction
- Time feature extraction
- Duration conversion
- Encoding categorical variables
- Feature selection
- Train-Test Split

---

## 🤖 Machine Learning Models

The following regression models were implemented:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

---

## 📈 Evaluation Metrics

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Data Preprocessing
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Comparison
11. Best Model Selection
12. Conclusion

---

## 📁 Project Structure

```
Flight-Fare-Prediction/
│
├── data/
│   └── Flight_Fare.csv
│
├── notebook/
│   └── Flight_Fare_Prediction.ipynb
│
├── images/
│   ├── airline_distribution.png
│   ├── fare_distribution.png
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   └── prediction_results.png
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/TanmayPatel143/Flight-Fare-Prediction.git
```

### 2. Navigate to the project folder

```bash
cd Flight-Fare-Prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open and run

```
flight flare.ipynb
```

---

## 📌 Results

- Successfully cleaned and preprocessed the flight fare dataset.
- Performed comprehensive Exploratory Data Analysis.
- Engineered useful date and time-based features.
- Trained multiple regression models.
- Compared model performance using standard regression metrics.
- Selected the best-performing model for flight fare prediction.

---

## ⚠️ Challenges Faced

- Handling missing values.
- Extracting useful information from date and time columns.
- Encoding categorical variables.
- Preventing model overfitting.
- Selecting the most suitable regression algorithm.

---

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV.
- Deploy the model using Flask, FastAPI, or Streamlit.
- Integrate real-time flight pricing APIs.
- Improve prediction accuracy using ensemble methods.
- Build an interactive web application for fare prediction.

---

## 👨‍💻 Author

**Darsh Patel**

GitHub: https://github.com/Darsh5202
