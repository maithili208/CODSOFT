# Titanic Survival Prediction 

This is my project for the **CODSOFT Tech Internship**.  
The task was to build a machine learning model to predict the survival of passengers on the Titanic dataset.

---

##  Project Overview
The Titanic dataset is one of the most famous datasets in data science.  
The goal is to predict whether a passenger survived or not based on features like age, sex, class, and more.

---

##  Dataset
- Dataset Source: [Kaggle Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)  
- Important columns used:
  - **Pclass** (Passenger Class)  
  - **Sex** (Male/Female)  
  - **Age**  
  - **SibSp** (Number of siblings/spouses aboard)  
  - **Parch** (Number of parents/children aboard)  
  - **Fare**  
  - **Embarked** (Port of Embarkation)

---

##  Steps Followed
1. **Data Loading & Exploration**
   - Imported the dataset.
   - Checked missing values and basic statistics.
   - Visualized data using seaborn and matplotlib.

2. **Data Preprocessing**
   - Handled missing values (Age, Embarked).
   - Converted categorical variables (`Sex`, `Embarked`) into numeric values.
   - Normalized/cleaned features.

3. **Model Building**
   - Applied **Logistic Regression** (baseline model).
   - Tried other algorithms (Decision Tree, Random Forest) for comparison.

4. **Model Evaluation**
   - Evaluated models using accuracy score and confusion matrix.
   - Selected the best performing model.

---

##  Results
- Logistic Regression achieved an accuracy of around **78–80%** on the test set.  
- Random Forest performed slightly better with accuracy above **80%**.  

---

##  Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

##  How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/maithili208/CODSOFT.git
