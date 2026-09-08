# Titanic Survival Classification Model

## AI & ML Internship — Week 2

This project was completed as part of the **AI & ML Internship Program 2026**.

The objective of this task was to move from data analysis into machine learning by building a **binary classification model** using the Titanic dataset.

The model predicts whether a passenger **survived or did not survive** based on selected passenger information.

---

## Project Objective

The main objectives of this project were to:

- Work with a real-world dataset
- Inspect and clean the data
- Identify features and a binary target variable
- Convert categorical data into numerical form
- Split the dataset into training and testing sets
- Train a Logistic Regression classification model
- Make predictions on unseen data
- Evaluate the model using classification metrics

---

## Dataset

The project uses the **Titanic dataset**.

The target variable is:

- `Survived = 0` → Did not survive
- `Survived = 1` → Survived

### Selected Features

The following features were used for prediction:

- `Pclass` — Passenger class
- `Sex` — Passenger gender
- `Age` — Passenger age
- `SibSp` — Number of siblings/spouses aboard
- `Parch` — Number of parents/children aboard
- `Fare` — Passenger fare
- `Embarked` — Port of embarkation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

The project followed the basic machine learning workflow:

```text
Dataset
   ↓
Data Inspection
   ↓
Data Cleaning
   ↓
Feature & Target Selection
   ↓
Categorical Data Encoding
   ↓
Train-Test Split
   ↓
Logistic Regression
   ↓
Predictions
   ↓
Model Evaluation
```

## Data Cleaning

Missing values in the `Age` column were filled using the median, while missing values in the `Embarked` column were filled using the mode.

## Data Encoding

Categorical columns such as `Sex` and `Embarked` were converted into numerical values using `pd.get_dummies()`.

## Train-Test Split

The dataset was split into **80% training data and 20% testing data** using `train_test_split()`.

## Machine Learning Model

A **Logistic Regression** model was trained to predict whether a passenger survived or did not survive.

## Model Evaluation

The model was evaluated using accuracy, precision, recall, and F1-score.

| Metric | Score |
|---|---:|
| Accuracy | 81.01% |
| Precision | 78.57% |
| Recall | 74.32% |
| F1-Score | 76.39% |

## Results

The model achieved **81.01% accuracy**, showing reasonable performance for predicting passenger survival. The results provide a good baseline for binary classification.

## Possible Improvement

The model could be improved by using additional features, feature engineering, and testing other classification algorithms such as Decision Tree.

---

## Project Structure

```text
week 2
├── train.csv
├── classification_model.ipynb
└── README.md
```

## How to Run

1. Install the required libraries:

```bash
pip install pandas numpy scikit-learn jupyter
```

2. Open `classification_model.ipynb` in Jupyter Notebook.
3. Make sure `train.csv` is in the same folder as the notebook.
4. Run all notebook cells in order.
5. View the model predictions and evaluation results.

---

## Key Learning Outcomes

Through this project, I learned:

- Data cleaning
- Feature and target selection
- Categorical data encoding
- Train-test splitting
- Logistic Regression
- Making predictions
- Model evaluation using classification metrics

---

## Conclusion

This project demonstrates the basic machine learning workflow for binary classification using the Titanic dataset and Scikit-learn.

The Logistic Regression model achieved **81.01% accuracy**, providing a reasonable baseline for predicting passenger survival.

---

## Internship Information

**Program:** AI & ML Internship Program 2026  
**Week:** 2 of 4  
**Task:** Build a Classification Model  
**Model:** Logistic Regression  
**Dataset:** Titanic Dataset
