# 🎒 Backpack Price Prediction

A Machine Learning project developed for the Kaggle competition **Playground Series - Season 5, Episode 2**. The objective is to predict backpack prices based on product characteristics such as brand, material, size, capacity, waterproof features, and other attributes.

This project demonstrates an end-to-end machine learning workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction generation.

---

## 🎯 Project Goal

The goal of this project is to build a regression model capable of accurately predicting backpack prices from product features.

Project tasks include:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Regression model training
* Model evaluation
* Kaggle submission generation
<img width="1217" height="79" alt="image" src="https://github.com/user-attachments/assets/f3092d5a-1c27-49f7-be28-d7cabe08b3cb" />

---

## 🏆 Competition

**Competition:** Playground Series - Season 5, Episode 2

**Kaggle Link:** https://www.kaggle.com/competitions/playground-series-s5e2

---

## 📂 Project Structure

```text
Backpack_prediction/
│
├── train.csv
├── test.csv
├── sample_submission.csv
├── notebook.ipynb
├── submission.csv
├── requirements.txt
└── README.md
```

### File Description

* **train.csv** – Training dataset used for model development.
* **test.csv** – Dataset used to generate predictions.
* **sample_submission.csv** – Kaggle submission template.
* **notebook.ipynb** – Complete analysis, preprocessing, training, and evaluation workflow.
* **submission.csv** – Final prediction file submitted to Kaggle.
* **requirements.txt** – Required Python libraries.
* **README.md** – Project documentation.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* LightGBM
* CatBoost
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📊 Dataset Features

The dataset contains backpack-related characteristics such as:

* Brand
* Material
* Size
* Color
* Style
* Capacity
* Weight Capacity
* Laptop Compartment
* Waterproof Feature

The target variable is:

* **Price**

---

## 🔍 Machine Learning Workflow

### 1. Data Preprocessing

* Missing value handling
* Categorical encoding
* Feature transformation
* Data cleaning

### 2. Exploratory Data Analysis

* Feature distributions
* Correlation analysis
* Outlier detection
* Target variable analysis

### 3. Model Training

Several regression models were tested, including:

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor
* LightGBM Regressor
* CatBoost Regressor

### 4. Model Evaluation

Model performance was evaluated using:

* RMSE (Root Mean Squared Error)
* Cross-validation

The best-performing model was selected for final prediction generation.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/SmbatSimonyan/Backpack_prediction.git
cd Backpack_prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Run all notebook cells to:

* Explore the data
* Train the model
* Evaluate performance
* Generate predictions

The final output file:

```text
submission.csv
```

can be uploaded directly to Kaggle.

---

## 📈 Results

The final model was improved through:

* Feature engineering
* Hyperparameter tuning
* Cross-validation
* Ensemble learning techniques

These optimizations helped improve prediction accuracy and leaderboard performance.

---

## 📚 Skills Demonstrated

This project showcases practical experience with:

* Machine Learning
* Regression Analysis
* Feature Engineering
* Data Preprocessing
* Model Evaluation
* Kaggle Competitions
* Python Data Science Ecosystem

---

## 🔗 Links

### GitHub Repository

https://github.com/SmbatSimonyan/Backpack_prediction

### Kaggle Competition

https://www.kaggle.com/competitions/playground-series-s5e2

---

## 👨‍💻 Author

**Smbat Simonyan**

GitHub: https://github.com/SmbatSimonyan

---

## ⭐ Support

If you found this project useful, consider giving the repository a star ⭐.

It helps support future Machine Learning and Data Science projects.
