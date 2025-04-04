# 🔍 Crime Rate Classification using Machine Learning

A beginner-friendly Machine Learning project that analyzes regional crime data and classifies areas as **High Crime** or **Low Crime** zones based on total crime metrics. Built using Python, Pandas, Seaborn, and Scikit-Learn.

---

## 📁 Dataset

A mock dataset containing crime statistics from different regions in India.  
Includes categories like:

- Murders
- Thefts
- Assaults
- Robberies
- Frauds

> ✅ The target variable is **`High_Crime`**, which is classified based on whether the total crime count is above the national average.

---

## 📊 Exploratory Data Analysis

Key insights:
- Total crime per region
- Heatmaps showing correlation between crime types
- Distribution of crime categories

Correlation Heatmap:  
![Screenshot 2025-04-04 192047](https://github.com/user-attachments/assets/819e436f-e25a-4897-9c0f-a8ab57f449f3)

---

## 🤖 Model Pipeline

### 💡 Algorithm Used:
- **Logistic Regression** for binary classification

### 🧪 Workflow:
1. Data cleaning & preparation
2. Feature-target split
3. Train-test split (80/20)
4. Model training using `sklearn`
5. Evaluation with accuracy, precision, recall, and confusion matrix

---

## 📈 Performance

| Metric       | Score |
|--------------|-------|
| Accuracy     | 95%   |
| Precision    | 100% (for High Crime) |
| Recall       | 90% (for High Crime) |
| F1-Score     | 95%   |

> 📌 Balanced performance across both classes!

---

## 🧠 Libraries Used

python
pandas  
numpy  
matplotlib  
seaborn  
scikit-learn  

---

## 📄 License  

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♀️ Author  

Made with 💙 by Archita
(https://github.com/arch5d)
