# Coffee Quality Analysis Using Clustering and Classification

This project is a comprehensive end-to-end data mining and analysis of coffee quality using real-world data. It was completed as part of the final project for the **Fundamentals of Data Science** course at DePaul University.

## 📌 Objective
To explore, preprocess, and analyze a coffee dataset to uncover patterns in quality and defects, and to apply machine learning techniques such as clustering and classification to evaluate coffee quality.

## 📊 What I Did

### 1. Data Preprocessing
- Handled missing values by imputing with medians or dropping columns with high NA counts.
- Converted categorical variables to factors.
- Scaled numeric features.
- Treated outliers in the altitude feature by capping at the 95th percentile.

### 2. Exploratory Data Analysis (EDA)
- Created histograms, boxplots, and correlation matrices.
- Explored patterns between country of origin and total cup points.
- Identified relationships between defects and overall coffee quality.

### 3. Clustering
- Applied **K-Means clustering** and used the elbow method to determine the optimal number of clusters (k = 3).
- Visualized clusters using **Principal Component Analysis (PCA)**.
- Analyzed cluster composition based on defect categories.

### 4. Classification
- Used the clusters as class labels to train classification models:
  - **K-Nearest Neighbors (KNN)**: Achieved 91.22% accuracy
  - **Random Forest**: Achieved 98.85% accuracy
- Evaluated using confusion matrix, precision, recall, and ROC-AUC (0.998)

## 🛠 Tools Used
- **R & RStudio**
- `tidyverse`, `ggplot2`, `cluster`, `caret`, `randomForest`, `factoextra`, `pROC`

## 📁 Files
- `Coffee_Quality_Analysis.Rmd` – Main R Markdown notebook with code and visualizations
- `Coffee_Quality_Report.html` – Final rendered report
- `README.md` – This file

## 🔍 Key Insights
- Countries like Ethiopia and Colombia tend to have higher cup scores.
- Altitude is positively correlated with quality but also contains outliers that affect model performance.
- Random Forest outperformed KNN by a large margin in classifying defect levels based on input features.

## 📈 Results
- **Random Forest Accuracy**: 98.85%
- **Precision**: 0.96  
- **Recall**: 0.98  
- **AUC**: 0.998

## 🙋‍♂️ Reflection
This project gave me real hands-on experience in data cleaning, modeling, and evaluation. I learned the importance of data preprocessing and model selection, and it strengthened my foundational understanding of how to handle real-world data using R.


---

