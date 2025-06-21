# 📊 Student Mental Health – Data Cleaning & Standardization

This project involves a real-world dataset on **student mental health**, focusing on cleaning and preprocessing steps essential for building reliable machine learning models.

---

## 🧠 Objective

The primary goal of this notebook is to:

- Understand the structure of the dataset
- Handle missing and inconsistent values
- Apply **standardization** to numerical features

This is a critical part of any **data science pipeline**, especially before performing classification, clustering, or dimensionality reduction.

---

## 📂 Dataset

- 📥 Source: [GitHub – Student Mental Health CSV](https://raw.githubusercontent.com/nileshely/Student-Mental-Health/main/Student%20Mental%20health.csv)
- 📊 Description: Contains demographic and mental health support data of students across various institutions.

---

## ⚙️ Technologies Used

- `Python`
- `Pandas`, `NumPy` – Data manipulation
- `Matplotlib`, `Seaborn` – Visualization
- `scikit-learn` – Standardization (`StandardScaler`)

---

## 🔧 Preprocessing Steps

1. **Loaded the dataset** from a remote GitHub source
2. **Explored and identified missing values**
3. **Handled missing data**
   - Used `median()` imputation for the `Age` column
4. **Applied Standardization**
   - Used `StandardScaler` to normalize numerical features
   - Ensures mean = 0 and standard deviation = 1 for each feature

---

## 📈 Why Standardization?

Standardization is essential when:
- Features are on different scales
- Distance-based models like KNN, SVM, PCA, etc., are applied

It improves model performance and ensures fair feature contribution.

---

## 🚀 Future Work

- Encode categorical variables (LabelEncoding / OneHotEncoding)
- Apply PCA for dimensionality reduction
- Train ML models (Logistic Regression, SVM, Random Forest)
- Evaluate performance using accuracy, precision, recall, F1-score

---

## 🙋‍♂️ Author

***Rudra Pratap Singh*  
*Aspiring Data Scientist | Learning with hands-on projects*  
📧 [LinkedIn Profile](https://www.linkedin.com/) *(Add your link here)*

---

## ⭐ Feedback

If you found this project helpful or have suggestions, feel free to ⭐ star the repo or connect with me on LinkedIn!

