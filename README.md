# 🛍️ Customer Shopping Behavior Analysis

A Data Analytics and Machine Learning project that analyzes customer shopping behavior to identify purchasing patterns and predict customer subscription status.

## 📌 Project Overview

This project performs data cleaning, preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning on a customer shopping behavior dataset.

The goal is to understand customer purchasing habits and build a model that predicts whether a customer is likely to subscribe based on their shopping behavior.

---

## 📂 Dataset

The dataset contains customer shopping information such as:

- Age
- Gender
- Purchase Amount
- Category
- Review Rating
- Previous Purchases
- Payment Method
- Discount Applied
- Frequency of Purchases
- Subscription Status
- And other customer-related attributes

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SQLAlchemy
- PostgreSQL / MySQL
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading

- Loaded customer dataset using Pandas.

### 2. Data Cleaning

- Checked missing values
- Filled missing Review Ratings using median values grouped by category
- Renamed columns
- Removed unnecessary columns

### 3. Feature Engineering

- Created Age Groups
- Converted purchase frequency into days
- Encoded categorical variables
- Applied One-Hot Encoding
- Prepared features for machine learning

### 4. Database Integration

Stored the cleaned dataset into:

- PostgreSQL
- MySQL

using SQLAlchemy.

### 5. Exploratory Data Analysis (EDA)

Visualizations include:

- Gender Distribution
- Age Distribution
- Product Category Analysis
- Purchase Amount Distribution
- Subscription Status Distribution

### 6. Machine Learning

Implemented:

- Logistic Regression
- Random Forest Classifier

Performed:

- Train-Test Split
- Model Training
- Prediction
- Accuracy Evaluation
- Classification Report
- Feature Importance Analysis
- Confusion Matrix

---

## 📈 Machine Learning Models

### Logistic Regression

Used as a baseline classification model for subscription prediction.

### Random Forest Classifier

Used to improve prediction accuracy and identify important features influencing subscription status.

---

## 📉 Visualizations

The project includes visualizations for:

- Customer Age Distribution
- Gender Distribution
- Purchase Amount
- Product Categories
- Subscription Status
- Confusion Matrix
- Feature Importance

---

## 📁 Project Structure

```
Customer_behavior_Project/
│
├── customer_behavior.ipynb      # Main Jupyter Notebook
├── customer.csv                 # Dataset
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Customer_behavior_Project.git
```

2. Navigate to the project

```bash
cd Customer_behavior_Project
```

3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn sqlalchemy pymysql psycopg2-binary
```

4. Open the notebook

```bash
jupyter notebook customer_behavior.ipynb
```

---

## 📌 Key Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Machine Learning
- Classification Models
- Database Integration
- SQL & Python

---

## 🎯 Future Improvements

- Hyperparameter tuning
- Deploy the model using Flask or Streamlit
- Interactive dashboard with Power BI or Tableau
- Add more machine learning algorithms
- Improve feature engineering

---

## 👨‍💻 Author

**Sarthak Navale**

If you found this project useful, feel free to ⭐ the repository.
