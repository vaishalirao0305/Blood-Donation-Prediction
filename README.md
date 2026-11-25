# 🩸 Blood Donation Prediction

## 📌 Project Overview
This project uses Machine Learning to predict whether a blood donor will donate blood again in March 2007.

The objective is to identify potential blood donors and support better blood donation planning.

## 🎯 Problem Statement
Predict whether a person is likely to donate blood again based on historical blood donation information.

## 📊 Dataset Information
- Dataset: Blood Transfusion Service Center
- Records used: 576
- Input features: 4
- Target variable: `Made Donation in March 2007`
- 1 = Donated
- 0 = Not Donated

## 🛠️ Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## ⚙️ Project Workflow
1. Data Loading and Exploration
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Scaling
5. Train-Test Split (80:20)
6. Model Building
7. Model Evaluation
8. Final Model Selection

## 🤖 Machine Learning Models
The following models were evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 77.59% | 62.50% | 17.86% | 27.78% |
| Decision Tree | 75.00% | 48.00% | 42.86% | 45.28% |
| Random Forest | 76.72% | 52.94% | 32.14% | 40.00% |
| KNN | 74.14% | 41.67% | 17.86% | 25.00% |

## 🏆 Final Model
**Decision Tree Classifier**

Decision Tree was selected based on its better recall and F1-score for identifying potential donors among the evaluated models.

## 💡 Conclusion
The project demonstrates how Machine Learning can help predict future blood donation behaviour.

The Decision Tree model achieved the highest recall and F1-score among the evaluated models, although identifying potential donors remains challenging due to class imbalance.

## 📁 Project Files
- `Blood_Donation_Prediction.ipynb` – Complete Jupyter Notebook containing data analysis, preprocessing, model training and evaluation.

## 👩‍💻 Author
**Vaishali Singamwar**

[GitHub](https://github.com/vaishalirao0305) | [LinkedIn](https://www.linkedin.com/in/vaishali-rao-06224214b/)# Blood-Donation-Prediction
Machine Learning project to predict whether a person will donate blood again.
