## 🧠 Titanic Survival Prediction Using Machine Learning

> Predicting who survives the Titanic disaster using logistic regression and random forest models.

### 📌 Project Overview

This project uses the famous Titanic dataset to build predictive models that determine whether a passenger survived or not. The goal is to apply machine learning techniques and gain insights from historical data through feature engineering and visual storytelling.

---

### 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib** & **Seaborn** (for visualization)
* **Scikit-learn** (for model building)
* **Jupyter Notebook**

---

### 📂 Dataset

* 📁 Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
* Includes details like:

  * Name, Age, Sex
  * Ticket Class (`Pclass`)
  * Fare, Cabin, Embarked port
  * Number of Siblings/Spouses (SibSp), Parents/Children (Parch)
  * Survival (Target variable)

---

### ⚙️ Workflow

1. **Data Cleaning**

   * Handled missing values in `Age`, `Embarked`, and `Fare`.
   * Dropped irrelevant columns (`Cabin`, `Name`, `Ticket`).
2. **Feature Engineering**

   * Encoded `Sex` and `Embarked`.
   * Selected key features for training.
3. **Exploratory Data Analysis**

   * Visualized survival trends by class, gender, age, and fare.
4. **Modeling**

   * Logistic Regression (baseline)
   * Random Forest Classifier (best performer)
5. **Evaluation**

   * Accuracy, Precision, Recall, F1-score
   * Confusion Matrix

---

### 📊 Results

| Model               | Accuracy | F1 Score |
| ------------------- | -------- | -------- |
| Logistic Regression | \~79%    | \~0.73   |
| Random Forest       | \~83%    | \~0.81   |

✅ Random Forest gave better performance overall.

---

### 📈 Visuals Included

* Survival by Gender
* Survival by Class
* Fare vs Survival Boxplot
* Age Distribution with KDE
* Feature Importance (from Random Forest)

*(All graphs available in the notebook)*

---

### 💾 Model Export

* Final Random Forest model exported as a `.pkl` file using `joblib` for deployment use.

---

### 🚀 How to Run

```bash
# Clone this repo
git clone https://github.com/yourusername/titanic-survival-prediction.git
cd titanic-survival-prediction

# Open Jupyter Notebook
jupyter notebook
```

---

### ✅ Future Improvements

* Hyperparameter tuning with GridSearchCV
* Model deployment using Streamlit or Flask
* Adding cross-validation for better generalization

---

### 🙋‍♂️ About Me

Hi! I'm **Jatin**, a B.Tech student in AI & Data Science. I'm passionate about making AI solutions practical, interpretable, and kinda fun to build. Let’s connect on [LinkedIn](https://www.linkedin.com/in/your-profile).

---

Let me know if you want this in a downloadable `.md` file — I’ll hook you up ⚡
Also, just share your GitHub repo name if you want help uploading it perfectly with folders!
