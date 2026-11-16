# Machine Learning and Data Analysis Projects
> **End-to-End Machine Learning, Classification, Regression, Clustering, and Exploratory Data Analysis Projects in Python**

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-EB6424?logo=xgboost&logoColor=white)](https://xgboost.ai/)
[![Optuna](https://img.shields.io/badge/Optuna-Hyperparameter_Tuning-blue)](https://optuna.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📌 Overview / Genel Bakış

This repository contains a curated collection of **8 comprehensive, production-grade Data Science and Machine Learning projects** developed using Python and Google Colaboratory. The projects span the entire data lifecycle: from exploratory data analysis (EDA) and data cleansing to advanced supervised learning (classification, regression), hyperparameter optimization (Bayesian search with Optuna), neural network modeling (MLP), and unsupervised pattern discovery (K-Means clustering and Apriori association rules).

*Bu depo; Python ve Google Colaboratory ortamında geliştirilmiş, Keşifsel Veri Analizi (EDA), veri temizliği, sınıflandırma, regresyon, hiperparametre optimizasyonu (Optuna), derin öğrenme (MLP), kümeleme (K-Means) ve birliktelik analizi (Apriori) alanlarını kapsayan **8 kapsamlı makine öğrenmesi ve veri analizi projesini** bir araya getirmektedir.*

---

## 🛠️ Technologies & Libraries / Kullanılan Teknolojiler

| Category | Tools & Libraries |
| :--- | :--- |
| **Language & Environment** | Python 3.10+, Google Colaboratory, Jupyter Notebook |
| **Data Processing & Manipulation** | Pandas, NumPy |
| **Data Visualization** | Matplotlib, Seaborn |
| **Machine Learning Algorithms** | Scikit-Learn, XGBoost, HistGradientBoosting, Random Forest, SVM |
| **Deep Learning** | TensorFlow / Keras (Multi-Layer Perceptron - MLP) |
| **Hyperparameter Optimization** | Optuna (Bayesian Optimization), GridSearchCV, RandomizedSearchCV |
| **Unsupervised Learning & Mining** | K-Means, Silhouette Analysis, Mlxtend (Apriori & Association Rules) |
| **Model Validation & Evaluation** | Stratified K-Fold, ROC-AUC, Precision-Recall Curves, Confusion Matrix |

---

## 🚀 Projects Catalog / Proje Kataloğu

| # | Project Name | Domain & Task | Models & Algorithms | Key Highlights & Metrics | Colab Notebook |
| :-: | :--- | :--- | :--- | :--- | :-: |
| 1 | **Heart Disease Prediction** | Supervised Binary Classification | Logistic Regression, Random Forest, Extra Trees, RBF-SVM, Optuna, Keras MLP | Full ML Pipeline, ROC-AUC, PR-AUC, CM & CR comparison | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Heart_Disease_Prediction_ML.ipynb) |
| 2 | **Healthcare Test Results Classification** | Multi-Class Classification | XGBoost, Random Forest, Logistic Regression, Optuna Tuning | 3-Class medical prediction (Normal, Abnormal, Inconclusive), One-Hot encoding | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Healthcare_Test_Results_Classification.ipynb) |
| 3 | **California Housing Price Regression** | Supervised Continuous Regression | Linear Regression, Random Forest Regressor, XGBoost, GridSearchCV | Spatial feature engineering, $R^2$ improvement, MAE reduction | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/California_Housing_Price_Regression.ipynb) |
| 4 | **Online Food Customer Feedback** | Sentiment & Feedback Classification | Logistic Regression, Decision Tree, Random Forest, XGBoost | Imbalanced dataset handling, Macro F1 optimization (0.9052 CV) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Online_Food_Customer_Feedback_Classification.ipynb) |
| 5 | **Diabetes Prediction Classification** | Medical Binary Classification | Logistic Regression, Feature Engineering, Median Imputation | Zero-value clinical correction, age-group median binning, F1-macro progression | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Diabetes_Prediction_Classification.ipynb) |
| 6 | **Customer Segmentation & Market Basket Analysis** | Clustering & Association Rules | K-Means Clustering, Mlxtend (Apriori & Association Rules) | RFM behavioral clustering, Support/Confidence/Lift rule mining | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Customer_Segmentation_and_Market_Basket_Analysis.ipynb) |
| 7 | **Online Food Dataset EDA & Cleaning** | Exploratory Data Analysis & Preprocessing | Statistical Profiling, Duplicate Detection, Categorical Cardinality | Duplicate removal, string sanitization, feature distribution analysis | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Online_Food_Dataset_EDA_and_Cleaning.ipynb) |
| 8 | **Mall Customer Segmentation (K-Means)** | Unsupervised Clustering | K-Means, Elbow (WCSS) Method, Silhouette Score Analysis | Optimal $k=5$ cluster discovery (Silhouette score: 0.5539), 2D Income-Spending segmentation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Mall_Customer_Segmentation_KMeans.ipynb) |

---

## 📂 Project Details / Proje Detayları

### 1. Heart Disease Prediction ML (`Heart_Disease_Prediction_ML.ipynb`)
- **Dataset:** Cleveland Heart Disease Dataset (UCI Machine Learning Repository).
- **Goal:** Predict the presence or absence of cardiovascular disease based on clinical indicators.
- **Workflow:** Comprehensive 15-step machine learning lab including statistical EDA (Chi-Square, correlation), rigorous data cleansing, scaling transformations, baseline comparison (DummyClassifier, Logistic Regression), advanced ensemble methods (Random Forest, Extra Trees, HistGradientBoosting, RBF-SVM), hyperparameter tuning via Optuna Bayesian search, and a deep learning Multi-Layer Perceptron (MLP) built with Keras.
- **Evaluation:** Precision, Recall, Macro F1, ROC-AUC, Precision-Recall curves, and Confusion Matrices.

### 2. Healthcare Test Results Classification (`Healthcare_Test_Results_Classification.ipynb`)
- **Dataset:** Kaggle Healthcare Dataset (`prasad22/healthcare-dataset`).
- **Goal:** Classify patient laboratory test results into three clinical categories (`Normal`, `Abnormal`, `Inconclusive`).
- **Workflow:** End-to-end multi-class classification pipeline incorporating categorical encoding (OneHotEncoder), numerical feature standardization, and high-performance gradient boosting with XGBoost and Optuna Bayesian optimization.

### 3. California Housing Price Regression (`California_Housing_Price_Regression.ipynb`)
- **Dataset:** California Housing Prices Dataset.
- **Goal:** Forecast continuous median house values (`MedHouseVal`) across California census blocks.
- **Workflow:** Extensive feature engineering (rooms per household, bedrooms per room, population per household), multi-model benchmarking (Linear Regression, Random Forest, XGBoost), and hyperparameter optimization via GridSearchCV. Achieves significant $R^2$ elevation and MAE reduction over baseline models.

### 4. Online Food Customer Feedback Classification (`Online_Food_Customer_Feedback_Classification.ipynb`)
- **Dataset:** Online Food Delivery Dataset (`sudarshan24byte/online-food-dataset`).
- **Goal:** Accurately classify consumer satisfaction feedback into positive or negative sentiments.
- **Workflow:** Data cleaning and deduplication, stratified train-test splitting, comparison of Decision Trees, Random Forests, and XGBoost, followed by hyperparameter tuning achieving a 0.9052 cross-validated Macro F1 score on imbalanced feedback data.

### 5. Diabetes Prediction Classification (`Diabetes_Prediction_Classification.ipynb`)
- **Dataset:** Pima Indians Diabetes Database (`uciml/pima-indians-diabetes-database`).
- **Goal:** Predict diabetes onset in high-risk patients.
- **Workflow:** Clinical domain-specific data preprocessing addressing biologically implausible zero values (glucose, blood pressure, skin thickness, insulin, BMI) via median imputation, correlation matrix analysis, and multi-stage feature engineering with age-group median categorization.

### 6. Customer Segmentation and Market Basket Analysis (`Customer_Segmentation_and_Market_Basket_Analysis.ipynb`)
- **Dataset:** Retail Groceries Dataset (`heeraldedhia/groceries-dataset`) and customer purchasing transaction profiles.
- **Goal:** Combine unsupervised clustering with association rule mining to uncover behavioral customer segments and cross-selling product associations.
- **Workflow:** K-Means clustering with Elbow method and Silhouette analysis for segmenting customers based on purchase frequency, average basket size, and product variety. Market basket analysis powered by the Apriori algorithm and association rules (Support, Confidence, Lift) analyzed per customer segment.

### 7. Online Food Dataset EDA and Cleaning (`Online_Food_Dataset_EDA_and_Cleaning.ipynb`)
- **Dataset:** Online Food Delivery Dataset.
- **Goal:** In-depth exploratory data analysis and data sanitization for downstream modeling.
- **Workflow:** Structural metadata audit, duplicate record isolation and removal, whitespace stripping across categorical attributes, redundancy analysis between target variables, and demographic distribution plotting.

### 8. Mall Customer Segmentation K-Means (`Mall_Customer_Segmentation_KMeans.ipynb`)
- **Dataset:** Mall Customers Dataset (`vjchoudhary7/customer-segmentation-tutorial-in-python`).
- **Goal:** Unsupervised customer grouping based on Annual Income and Spending Score.
- **Workflow:** Kagglehub automated dataset loading, 2D feature extraction, Within-Cluster Sum of Squares (WCSS) Elbow curve plotting, and Silhouette score optimization ($k=2..8$). Confirms the global optimal clustering at $k=5$ with a Silhouette score of 0.5539.

---

## 💻 Getting Started / Kurulum ve Çalıştırma

### Direct Colab Execution
Click any of the **"Open in Colab"** badges above to launch and execute the notebooks directly in your browser without local installation.

### Local Environment Setup
```bash
# 1. Clone the repository
git clone https://github.com/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects.git
cd Machine-Learning-and-Data-Analysis-Projects

# 2. Create and activate a virtual environment
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Linux/macOS:
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt
```

---

## 👨‍💻 Author / Yazar

**Burak GÜLDALI**
- GitHub: [@BurakGuldal10](https://github.com/BurakGuldal10)
- Repository: [Machine-Learning-and-Data-Analysis-Projects](https://github.com/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects)

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
