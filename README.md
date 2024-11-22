# Titanic Survival Prediction

This project predicts the likelihood of survival of passengers aboard the Titanic using machine learning techniques. The goal is to identify patterns in the data, such as how factors like age, gender, and socio-economic status affected survival rates.

---

## Features of the Dataset
The dataset contains information on Titanic passengers, including:
- **Name**
- **Age**
- **Gender**
- **Socio-economic class (Pclass)**
- **Number of siblings/spouses aboard (SibSp)**
- **Number of parents/children aboard (Parch)**
- **Embarked location**

---

## Key Insights
- **Survival Rates by Gender**: Females had a much higher survival rate compared to males.
- **Survival Rates by Class**: Passengers in higher classes had better chances of survival.
- **Age Distribution**: Younger passengers were more likely to survive, as seen in survival rates for different age groups.

Graphs and statistical summaries support these insights.

---

## Workflow
1. **Data Preprocessing**:
   - Missing values in `Age` were imputed.
   - Irrelevant columns such as `PassengerId` and `Ticket` were removed.
   - Features like `Family_Size` were engineered.
   - Categorical variables like `Sex` and `Embarked` were converted into numeric form.

2. **Exploratory Data Analysis**:
   - Insights were visualized using histograms, bar plots, and scatter plots.
   - Statistical summaries of survival rates by `Gender`, `Pclass`, and `Age`.

3. **Model Training**:
   - A **Random Forest Classifier** was used for prediction.
   - Achieved high accuracy on training data.

4. **Model Evaluation**:
   - Feature importance analysis was performed to identify key predictors of survival.

---

## How to Run
1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
