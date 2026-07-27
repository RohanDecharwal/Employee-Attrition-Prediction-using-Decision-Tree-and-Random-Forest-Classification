# AI-ML Assignment – 5
## Employee Attrition Prediction using Decision Tree and Random Forest Classification

### 👨‍🎓 Student Details

- **Name:** Rohan Ramdhan Decharwal
- **Course:** AI/ML Internship
- **Batch:** Batch 1(A)
- **Mentor:** Nishant Shrivastava

---

## 📌 Objective

The objective of this project is to develop machine learning models that predict employee attrition using the **IBM HR Analytics Employee Attrition & Performance Dataset**. Two classification algorithms, **Decision Tree** and **Random Forest**, are implemented and compared to determine which model provides better prediction performance for employee attrition.

---

## 📂 Dataset

**IBM HR Analytics Employee Attrition & Performance Dataset**

🔗 **Kaggle Dataset:**  
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

### Features

The dataset contains employee demographic, job-related, and work environment information such as:

- Age
- Business Travel
- Department
- Education
- Gender
- Job Role
- Monthly Income
- Job Satisfaction
- Years at Company
- Overtime
- Performance Rating
- Work-Life Balance
- And several other employee-related attributes.

### Target Variable

- **Attrition (Yes/No)**

---

## 🛠 Libraries Used

The following Python libraries were used in this project:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## ⚙️ Methodology

The project was completed using the following steps:

1. Loaded the dataset using Pandas.
2. Displayed the first five records, dataset information, and summary statistics.
3. Checked for missing values.
4. Removed unnecessary columns (if any).
5. Encoded categorical variables.
6. Split the dataset into **80% training** and **20% testing**.
7. Built two classification models:
   - **Decision Tree Classifier**
   - **Random Forest Classifier (100 estimators)**
8. Trained both models using the same training dataset.
9. Predicted employee attrition on the test dataset.
10. Evaluated both models using:
    - Accuracy Score
    - Precision
    - Recall
    - F1-Score
11. Generated:
    - Confusion Matrix for both models
    - Feature Importance plot for the Random Forest model
12. Compared the performance of both models.

---

## 📊 Results

Both Decision Tree and Random Forest models were successfully trained to predict employee attrition. Their performance was evaluated using Accuracy, Precision, Recall, and F1-Score. Confusion Matrices were used to visualize the classification results, while the Random Forest Feature Importance plot identified the most influential factors affecting employee attrition. The comparison showed that Random Forest generally produced more reliable and accurate predictions than the Decision Tree model.

---

## 📈 Model Comparison

| Decision Tree | Random Forest |
|---------------|---------------|
| Simple and easy to interpret | More accurate and robust |
| Can easily overfit the training data | Reduces overfitting by combining multiple trees |
| Faster to train | Slightly slower due to multiple estimators |
| Less stable with small changes in data | Produces more consistent predictions |

Overall, the **Random Forest Classifier** achieved better classification performance because it combines the predictions of multiple decision trees, reducing variance and improving generalization.

---

## 📝 Conclusion

This project demonstrates the use of Decision Tree and Random Forest classifiers for predicting employee attrition based on demographic and workplace-related attributes. Both models successfully classified employees who were likely to leave the organization. However, the Random Forest model generally outperformed the Decision Tree model by achieving higher accuracy and better overall classification metrics. This improvement is due to the ensemble learning approach, where multiple decision trees work together to reduce overfitting and improve prediction stability. A limitation of the Decision Tree algorithm is its tendency to overfit the training data, especially when the tree becomes very deep. On the other hand, Random Forest requires greater computational resources and is less interpretable than a single Decision Tree. Overall, Random Forest provides a more reliable solution for employee attrition prediction.

---

## 📁 Repository Structure

```
Assignment-5/
│── Assignment_5.ipynb
│── README.md
```

---

## 👤 Author

**Rohan Ramdhan Decharwal**

**AI/ML Internship – Batch 1(A)**

**Mentor:** Nishant Shrivastava
