# Missing Value Imputation

## 📘 Project Overview

**Missing Value Imputation** is a project focused on identifying and applying effective techniques to handle missing data in real-world datasets. Missing data can lead to biased results and reduced performance in machine learning models. This project systematically compares several imputation methods under various missingness scenarios to determine the most reliable solutions.

---

## 🎯 Objectives

- Understand the impact of missing values in datasets.
- Implement and compare multiple imputation techniques.
- Evaluate each method using statistical metrics (MAE, RMSE).
- Provide practical guidance for data preprocessing in ML pipelines.

---

## 📂 Datasets Used

- Loan Approval
- Wine Quality
- Ionosphere
- Heart Disease
- Balance Scale
- Lung Cancer
- Soybean Small

Each dataset is preprocessed and missingness is artificially introduced using:
- MCAR (Missing Completely at Random)
- MAR (Missing at Random)
- MNAR (Missing Not at Random)

---

## 🧰 Tools & Technologies

- **Language**: Python 3.7+
- **Libraries**:  
  - `pandas`, `numpy` (Data handling)  
  - `scikit-learn` (Imputation & Evaluation)  
  - `fancyimpute`, `miceforest` (Advanced Imputation)  
  - `matplotlib`, `seaborn` (Visualization)  
  - `Jupyter Notebook` (Development environment)

---

## 🧪 Imputation Methods

1. **Mean/Median Imputation**  
2. **K-Nearest Neighbors (KNN)**  
3. **Random Forest Imputation**  
4. **Multiple Imputation by Chained Equations (MICE)**

---

## 📈 Evaluation Metrics

- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**

Visual comparisons via bar charts and box plots illustrate the accuracy of each method across datasets.

---

## 📌 Key Results

- Random Forest imputation performed best on most datasets (Loan, Heart Disease, Wine).
- MICE was most effective for high-dimensional datasets (e.g., Ionosphere).
- Simple imputation (Mean/Median) was sufficient for smaller or low-variance datasets (e.g., Lung Cancer).

---

## 🔬 Future Work

- Integration of deep learning-based imputation (Autoencoders, GANs)
- Support for time-series and sequential data
- Development of a user-friendly web tool or package

---

## 📑 Project Structure

