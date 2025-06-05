# 🎓 Placement Prediction using Logistic Regression (Beginner ML Project)

This is a **learning project** where I built a simple Logistic Regression model to predict whether a student gets placed based on their **CGPA** and **IQ**.

---

## 📌 Goal

Learn how to:
- Work with a dataset
- Preprocess and clean data
- Apply Logistic Regression
- Evaluate and understand model results

---

## 📁 Dataset Overview

The dataset contains the following columns:
- `cgpa` – Student’s grade point average
- `iq` – Intelligence Quotient
- `placement` – Target variable (1 = Placed, 0 = Not placed)

---

## 🧪 Steps Followed

1. **Exploratory Data Analysis**
   - Plotted histograms and checked for normality
   - Used Shapiro-Wilk test to statistically check distribution

2. **Outlier Handling**
   - Used `IsolationForest` to detect and remove outliers

3. **Feature Scaling**
   - Applied `StandardScaler` to normalize `cgpa` and `iq`

4. **Model Building**
   - Used `LogisticRegression` from `scikit-learn`
   - Split data into training and testing (80/20)

5. **Model Evaluation**
   - Confusion matrix
   - Classification report (accuracy, precision, recall, F1-score)

---

## 🛠️ Tools & Libraries Used

- `pandas`, `numpy` – data handling
- `matplotlib`, `seaborn` – visualization
- `scikit-learn` – ML models and evaluation
- `scipy` – statistical testing

---

## 📊 Sample Visualizations

- Histograms of `cgpa` and `iq`
- Decision boundary plot (optional)
- Confusion matrix

---

## 🔍 What I Learned

- How logistic regression works
- The importance of preprocessing (scaling)
- How to evaluate model performance using various metrics

---

## 🚀 What's Next

- Try other models like Decision Tree or Random Forest
- Add more features (like soft skills or projects)
- Learn about cross-validation and hyperparameter tuning

---

## 📚 Disclaimer

This is a **learning project** for educational purposes. The dataset and model are simple and meant to help me understand the basics of machine learning and model evaluation.

