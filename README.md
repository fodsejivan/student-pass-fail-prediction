# student-pass-fail-prediction
# 🎓 Student Success Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a student will **Pass or Fail** based on key factors like study hours, attendance, past scores, and sleep hours.

It uses **Logistic Regression** along with **Feature Scaling (StandardScaler)** to build an accurate classification model.

---

## 🚀 Features

* Data preprocessing using **Pandas & NumPy**
* Label encoding for categorical variables
* Feature scaling using **StandardScaler**
* Model training using **Logistic Regression**
* Model evaluation using:

  * Classification Report
  * Confusion Matrix
* User input prediction (custom values)

---

## 🧠 Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 📂 Dataset

The dataset contains the following features:

* StudyHours 📚
* Attendance 📊
* PastScore 📝
* SleepHours 😴
* Internet (Categorical)
* Passed (Target Variable)

---

## ⚙️ How It Works

1. Load dataset from Excel file
2. Clean column names (remove extra spaces)
3. Encode categorical columns using LabelEncoder
4. Apply feature scaling using StandardScaler
5. Split data into training and testing sets
6. Train model using Logistic Regression
7. Evaluate performance using classification report & confusion matrix
8. Take user input and predict result

---

## 📊 Model Evaluation

* Confusion Matrix visualization using Seaborn heatmap
* Precision, Recall, F1-score using classification report




## 🔮 Example Prediction

User Input:

* Study Hours: 5
* Attendance: 80
* Past Score: 65
* Sleep Hours: 7

👉 Output: **Pass / Fail**

---

## 📸 Output

* Classification Report
* Confusion Matrix (heatmap)


## 💡 Future Improvements

* Use advanced models (Random Forest, SVM)
* Deploy using Flask / Streamlit
* Add real-world dataset
* Improve accuracy with hyperparameter tuning

---

## 👨‍💻 Author

**Jivan Santosh Fodase**


---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
