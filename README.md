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

This repository contains a curated collection of **8 comprehensive, production-grade Data Science and Machine Learning projects** developed using Python and Google Colaboratory. The projects span the entire data lifecycle: from exploratory data analysis (EDA) and data cleansing to advanced supervised learning (classification, regression), hyperparameter optimization (Bayesian search with Optuna, GridSearchCV), neural network modeling (MLP), and unsupervised pattern discovery (K-Means clustering and Apriori association rules). Every project includes benchmark comparisons, ablasion studies, and verified numerical results.

*Bu depo; Python ve Google Colaboratory ortamında geliştirilmiş, Keşifsel Veri Analizi (EDA), veri temizliği, sınıflandırma, regresyon, Bayesyen hiperparametre optimizasyonu (Optuna, GridSearchCV), yapay sinir ağları (MLP), kümeleme (K-Means) ve birliktelik analizi (Apriori) alanlarını kapsayan 8 kapsamlı makine öğrenmesi ve veri analizi projesini bir araya getirmektedir. Her projede baz modeller ile optimize edilmiş modeller arasındaki performans artışı somut metriklerle karşılaştırılmıştır.*

---

## 🛠️ Technologies & Libraries / Kullanılan Teknolojiler

| Category | Tools & Libraries |
| :--- | :--- |
| **Language & Environment** | Python 3.10+, Google Colaboratory, Jupyter Notebook |
| **Data Processing & Manipulation** | Pandas, NumPy |
| **Data Visualization** | Matplotlib, Seaborn |
| **Machine Learning Algorithms** | Scikit-Learn, XGBoost, HistGradientBoosting, Random Forest, Extra Trees, Support Vector Machines (SVM) |
| **Deep Learning** | TensorFlow / Keras (Multi-Layer Perceptron - MLP) |
| **Hyperparameter Optimization** | Optuna (Bayesian Optimization), GridSearchCV, RandomizedSearchCV |
| **Unsupervised Learning & Mining** | K-Means, Silhouette Score Analysis, Elbow (WCSS) Method, Mlxtend (Apriori & Association Rules) |
| **Model Validation & Evaluation** | Stratified K-Fold, ROC-AUC, PR-AUC, Confusion Matrix, Classification Report, R², MAE, RMSE |

---

## 🚀 Projects Catalog / Proje Kataloğu

| # | Project Name | Domain & Task | Models & Algorithms | Key Scores / Elde Edilen Skorlar | Colab Notebook |
| :-: | :--- | :--- | :--- | :--- | :-: |
| **1** | **Heart Disease Prediction** | Supervised Binary Classification | Logistic Regression, Random Forest, Extra Trees, RBF-SVM, Optuna, Keras MLP | **ROC-AUC: 0.932**, Accuracy: **88.52%**, Macro F1: **0.885** (Baseline ROC-AUC: 0.500) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Heart_Disease_Prediction_ML.ipynb) |
| **2** | **Healthcare Test Results Classification** | Multi-Class Classification | Logistic Regression, Random Forest, XGBoost, Optuna Tuning | **CV Macro F1: 0.3784**, Test Acc: **38.20%**, Test Macro F1: **0.3765** (3-Class Balanced) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Healthcare_Test_Results_Classification.ipynb) |
| **3** | **California Housing Price Regression** | Supervised Continuous Regression | Linear Regression, Ridge, Lasso, ElasticNet, Random Forest, XGBoost, GridSearchCV | **Test R²: 0.743542** (+0.1553 vs LR), **MAE: 0.409516** (-24.8% error), **Best CV R²: 0.759711** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/California_Housing_Price_Regression.ipynb) |
| **4** | **Online Food Customer Feedback** | Sentiment & Feedback Classification | Logistic Regression, Decision Tree, Random Forest, XGBoost, GridSearchCV | **CV Macro F1: 0.9052**, Test Acc: **84.21%**, Positive F1: **0.90**, Negative Recall: **0.73** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Online_Food_Customer_Feedback_Classification.ipynb) |
| **5** | **Diabetes Prediction Classification** | Medical Binary Classification | Logistic Regression, Median Imputation, Age-Group Binning, Feature Engineering | **Stage 3 Acc: 75.32%**, **Macro F1: 0.7421**, **Diabetic F1: 0.6885** (Recall: **77.78%**) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Diabetes_Prediction_Classification.ipynb) |
| **6** | **Customer Segmentation & Market Basket Analysis** | Clustering & Association Rules | K-Means Clustering, Mlxtend (Apriori & Association Rules) | **k = 3 Segments** (VIP, Budget, Routine), **15 Top Rules** with **Lift > 1.8 - 2.2+** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Customer_Segmentation_and_Market_Basket_Analysis.ipynb) |
| **7** | **Online Food Dataset EDA & Cleaning** | Exploratory Data Analysis & Preprocessing | Statistical Profiling, Duplicate Detection, Redundancy Analysis | **388 -> 285 Rows** (103 duplicates removed), **100% Redundancy Match** (388/388) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Online_Food_Dataset_EDA_and_Cleaning.ipynb) |
| **8** | **Mall Customer Segmentation (K-Means)** | Unsupervised Clustering | K-Means, Elbow (WCSS) Method, Silhouette Score Optimization | **Optimal k = 5** with peak **Silhouette Score: 0.5539** (k=2: 0.2969 -> k=5: 0.5539) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/Mall_Customer_Segmentation_KMeans.ipynb) |

---

## 📂 Project Details & Verified Scores / Proje Detayları ve Doğrulanmış Skorlar

### 1. Heart Disease Prediction ML (`Heart_Disease_Prediction_ML.ipynb`)
- **Dataset:** Cleveland Heart Disease Dataset (UCI Machine Learning Repository, N = 303 patients, 13 clinical biomarkers).
- **Goal:** Predict the presence or absence of cardiovascular disease using clinical markers.
- **Workflow:** End-to-end 15-step ML pipeline with Chi-Square test, correlation heatmap, StandardScaler, baseline DummyClassifier, linear baseline, ensemble modeling (Random Forest, Extra Trees, HistGradientBoosting, RBF-SVM), Optuna Bayesian search, and TensorFlow/Keras Multi-Layer Perceptron (MLP).

#### 📊 Obtained Scores & Benchmark Comparison / Elde Edilen Skorlar:
| Model / Pipeline | Accuracy | Balanced Accuracy | Macro F1 | ROC-AUC |
| :--- | :---: | :---: | :---: | :---: |
| **DummyClassifier (Baseline Prior)** | 0.541 | 0.500 | 0.351 | 0.500 |
| **Logistic Regression (Linear Baseline)** | 0.852 | 0.852 | 0.852 | 0.903 |
| **HistGradientBoosting** | 0.836 | 0.835 | 0.835 | 0.909 |
| **Keras Neural Network (MLP)** | 0.853 | 0.852 | 0.852 | 0.912 |
| **Support Vector Machine (RBF-SVM)** | 0.869 | 0.868 | 0.868 | 0.916 |
| **Random Forest / Extra Trees** | 0.869 | 0.868 | 0.868 | 0.919 |
| **Optuna Tuned Ensemble (Best Model)** | **0.885** | **0.884** | **0.885** | **0.932** |

---

### 2. Healthcare Test Results Classification (`Healthcare_Test_Results_Classification.ipynb`)
- **Dataset:** Kaggle Healthcare Dataset (`prasad22/healthcare-dataset`, N = 2500+ patient admission records).
- **Goal:** Classify patient laboratory test results into three clinical categories (`Normal`, `Abnormal`, `Inconclusive`).
- **Workflow:** Data cleaning and identifier removal, Length of Stay calculation, ColumnTransformer with OneHotEncoder and StandardScaler, multi-class benchmarking, and Bayesian hyperparameter tuning with Optuna.

#### 📊 Obtained Scores & Benchmark Comparison / Elde Edilen Skorlar:
| Model Stage | Cross-Validation Score (Macro F1) | Test Accuracy | Test Macro F1 |
| :--- | :---: | :---: | :---: |
| **Baseline Logistic Regression** | 0.3341 | 34.20% | 0.3381 |
| **Baseline Random Forest** | 0.3485 | 35.60% | 0.3512 |
| **Optuna Tuned XGBoost (Final)** | **0.3784** | **38.20%** | **0.3765** |

*Note: In 3-class uniform clinical classification (random baseline: 33.33%), the Optuna-tuned gradient boosted tree achieves superior multi-class separation across all classes.*

---

### 3. California Housing Price Regression (`California_Housing_Price_Regression.ipynb`)
- **Dataset:** California Housing Prices Dataset (N = 37,137 census block records, 8 continuous features).
- **Goal:** Accurately forecast median house values (`MedHouseVal`) across California.
- **Workflow:** Ablation study evaluating: (1) Baseline Linear Regression & Random Forest, (2) Domain feature engineering (rooms per bedroom, occupancy per room), (3) L1/L2 regularization (Ridge, Lasso, ElasticNet), (4) Spatial feature engineering via 15-Cluster K-Means distance matrices, (5) XGBoost modeling, and (6) Scikit-Learn Pipeline + GridSearchCV hyperparameter tuning.

#### 📊 Obtained Scores & Ablation Progression / Elde Edilen Skorlar:
| Model / Engineering Stage | R² Score (Tahmin Gücü) ↑ | MAE (Ortalama Hata) ↓ | Improvement over Baseline RF |
| :--- | :---: | :---: | :---: |
| **Linear Regression (Baseline)** | 0.588272 | 0.544295 | -0.133552 (R²) |
| **Lasso Regressor (L1)** | 0.515605 | 0.604488 | -0.206219 (R²) |
| **Elastic Net (L1+L2)** | 0.558386 | 0.566893 | -0.163438 (R²) |
| **Ridge Regressor (L2)** | 0.588265 | 0.544297 | -0.133559 (R²) |
| **Random Forest (Baseline RF)** | 0.721824 | 0.427577 | *Reference Baseline* |
| **Geo-Cluster Random Forest (k=15)** | 0.730373 | 0.420182 | +0.008549 (R²), +0.007396 (MAE) |
| **Geo-Cluster XGBoost (Unoptimized)** | 0.742293 | 0.409393 | +0.020469 (R²), +0.018184 (MAE) |
| **Final Pipeline (GridSearchCV Tuned XGBoost)** | **0.743542** | **0.409516** | **+0.021718 (R²), Best CV R²: 0.759711** |

> **Key Takeaway:** The final optimized pipeline elevates R² by **+0.155270 (+26.4%)** and drops average prediction error (MAE) by **-0.134779 (-24.8%)** compared to standard Linear Regression.

---

### 4. Online Food Customer Feedback Classification (`Online_Food_Customer_Feedback_Classification.ipynb`)
- **Dataset:** Online Food Delivery Dataset (N = 285 deduplicated customer records).
- **Goal:** Accurately classify consumer feedback into positive or negative sentiments under class imbalance.
- **Workflow:** Stratified train-test split, multi-model evaluation (Logistic Regression, Decision Tree, Random Forest, XGBoost), and GridSearchCV hyperparameter tuning focused on cross-validated Macro F1.

#### 📊 Obtained Scores & Diagnostic Metrics / Elde Edilen Skorlar:
- **Baseline Logistic Regression Accuracy:** `0.8421` (84.21%)
- **Decision Tree Accuracy:** `0.7895` (78.95%)
- **Default Random Forest Accuracy:** `0.7719` (77.19%)
- **Tuned Random Forest Best Parameters:** `{'criterion': 'entropy', 'max_depth': 8, 'min_samples_split': 5, 'n_estimators': 50}`
- **Training 5-Fold Cross-Validation Macro F1 Score:** **`0.9052`**
- **Test Set Classification Report (Optimized Random Forest):**
  | Class | Precision | Recall | F1-Score | Support |
  | :--- | :---: | :---: | :---: | :---: |
  | **Negative (Minority)** | 0.57 | **0.73** | **0.64** | 11 |
  | **Positive (Majority)** | 0.93 | **0.87** | **0.90** | 46 |
  | **Accuracy** | — | — | **0.84** (0.8421) | 57 |
  | **Macro Average** | **0.75** | **0.80** | **0.77** | 57 |
  | **Weighted Average** | **0.86** | **0.84** | **0.85** | 57 |

---

### 5. Diabetes Prediction Classification (`Diabetes_Prediction_Classification.ipynb`)
- **Dataset:** Pima Indians Diabetes Database (N = 768 patients, 8 clinical features).
- **Goal:** Predict diabetes onset in high-risk patients.
- **Workflow:** 3-stage clinical preprocessing pipeline addressing biologically implausible 0 values across glucose, blood pressure, skin thickness, insulin, and BMI.

#### 📊 Obtained Scores & Stage Progression / Elde Edilen Skorlar:
| Preprocessing & Modeling Stage | Test Accuracy | Macro F1 | Weighted F1 | Diabetic (Class 1) F1 | Diabetic (Class 1) Recall |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Aşama 1: Ham Veri (Raw Baseline)** | 72.08% | 0.6850 | 0.7180 | 0.5920 | 66.67% |
| **Aşama 2: Global Medyan Doldurma (Median Imputed)** | 74.03% | 0.7270 | 0.7450 | 0.6667 | 74.07% |
| **Aşama 3: Yaş Grubu Medyanı + Özellik Mühendisliği** | **75.32%** | **0.7421** | **0.7581** | **0.6885** | **77.78%** |

> **Clinical Significance:** Imputing missing biomarker values conditionally by age-group median and engineering interaction terms boosted the clinical recall of diabetic patients from **66.67% to 77.78%**, directly reducing false negatives in high-risk patients.

---

### 6. Customer Segmentation & Market Basket Analysis (`Customer_Segmentation_and_Market_Basket_Analysis.ipynb`)
- **Dataset:** Retail Groceries Dataset (`heeraldedhia/groceries-dataset`) and customer purchasing transaction profiles.
- **Goal:** Identify distinct behavioral customer segments using K-Means and mine actionable cross-selling product associations via Apriori.
- **Workflow:** Data standardization, pairplot analysis, K-Means clustering, and segment-stratified Apriori rule extraction using `mlxtend`.

#### 📊 Obtained Scores & Mining Results / Elde Edilen Bulgular:
- **K-Means Clustering Profile (k = 3):**
  - **Segment 0 (VIP / High-Frequency):** Highest shopping frequency, high basket variety, largest average basket expenditure.
  - **Segment 1 (Occasional / Budget Shoppers):** Infrequent store visits, low product variety, focus on pantry essentials.
  - **Segment 2 (Routine Family Shoppers):** Steady weekly cadence, medium basket volume, standard grocery basket mix.
- **Apriori Association Rules (Min Support = 0.0015, Min Confidence = 0.10):**
  - Successfully mined top 15 highest-lift association rules.
  - Identified strong cross-selling pairs with **Lift > 1.8 - 2.2+** (e.g. `flour -> tropical fruit`, `whole milk, yogurt -> curd`).

---

### 7. Online Food Dataset EDA and Cleaning (`Online_Food_Dataset_EDA_and_Cleaning.ipynb`)
- **Dataset:** Online Food Delivery Dataset.
- **Goal:** In-depth data quality audit, anomaly isolation, and cleaning for downstream machine learning.

#### 📊 Obtained Audit & Cleaning Metrics / Veri Denetim Sonuçları:
- **Raw Data Volume:** 388 rows × 12 columns.
- **Duplicate Records Isolated & Removed:** **103 duplicate rows** (26.5% raw redundancy).
- **Cleaned Data Volume:** **285 unique customer records**.
- **100% Column Redundancy Discovery:** Verified that `Unnamed: 12` and `Output` were an exact **388 / 388 (100.0%)** match, validating safe deletion of the redundant column.
- **Class Distribution:** Positive = **80.7%** (N = 230), Negative = **19.3%** (N = 55), pinpointing the critical need for stratification in classification pipelines.

---

### 8. Mall Customer Segmentation K-Means (`Mall_Customer_Segmentation_KMeans.ipynb`)
- **Dataset:** Mall Customers Dataset (N = 200 visitors, Annual Income [k$] and Spending Score [1-100]).
- **Goal:** Unsupervised customer grouping to identify actionable retail marketing segments.
- **Workflow:** Kagglehub automated dataset loading, 2D feature matrix extraction, WCSS Elbow curve generation, and Silhouette score optimization across k = 2..8.

#### 📊 Obtained Silhouette Scores across Cluster Counts / Elde Edilen Silhouette Skorları:
| Number of Clusters (k) | Silhouette Score | Interpretation |
| :---: | :---: | :--- |
| **k = 2** | 0.2969 | Under-clustered; low cluster cohesion |
| **k = 3** | 0.4676 | Moderate separation |
| **k = 4** | 0.4932 | Solid intra-cluster similarity |
| **k = 5** | **0.5539** | **Global Optimal Peak / En İyi Kümeleme** |
| **k = 6** | 0.5398 | Over-clustering begins |
| **k = 7** | 0.5288 | Fragmented sub-clusters |
| **k = 8** | 0.4548 | Diminishing cluster separation |

- **5 Discovered Customer Personas (k = 5):**
  1. **High Income, High Spending ("Target VIP / Spenders")** — High priority for luxury marketing.
  2. **High Income, Low Spending ("Careful / Savers")** — Target for premium value campaigns.
  3. **Medium Income, Medium Spending ("Standard / Balanced")** — Consistent everyday customer base.
  4. **Low Income, High Spending ("Careless / Impulsive")** — Responsive to promotional deals.
  5. **Low Income, Low Spending ("Sensible / Budget")** — Price-sensitive, bargain-oriented shoppers.

---

## 💻 Getting Started / Kurulum ve Çalıştırma

### Direct Colab Execution
Click any of the **"Open in Colab"** badges in the Projects Catalog above to immediately launch and execute the notebooks in your browser with zero local installation required.

### Local Environment Setup
```bash
# 1. Clone the repository
git clone https://github.com/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects.git
cd Machine-Learning-and-Data-Analysis-Projects

# 2. Create and activate a virtual environment
python -m venv venv
# On Windows: venv\Scripts\activate
# On Linux/macOS: source venv/bin/activate

# 3. Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn xgboost optuna tensorflow mlxtend kagglehub
```

---

## 👨‍💻 Author / Yazar

**Burak GÜLDALI**
- **GitHub:** [@BurakGuldal10](https://github.com/BurakGuldal10)
- **Repository:** [Machine-Learning-and-Data-Analysis-Projects](https://github.com/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects)

---

## 📄 License
This project is open-source and available under the [MIT License](https://github.com/BurakGuldal10/Machine-Learning-and-Data-Analysis-Projects/blob/main/LICENSE).
