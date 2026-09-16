# Regression and Clustering on Real-World Data

## Vortex Tech AI & ML Internship 2026 — Week 3

This project demonstrates two machine learning techniques using real-world datasets:

1. **Regression** — predicting a continuous numerical value.
2. **K-Means Clustering** — discovering hidden groups in customer data.

## Project Objectives

- Clean and prepare real-world datasets.
- Build and evaluate a regression model.
- Predict house sale prices using Random Forest Regression.
- Evaluate the regression model using RMSE and R².
- Apply K-Means clustering to customer data.
- Use StandardScaler for feature scaling.
- Determine a suitable number of clusters using the Elbow Method.
- Visualize and interpret the resulting customer segments.

## Datasets

### 1. House Prices Dataset

The House Prices dataset is used for the regression task.

**Target:** `SalePrice`

Selected features:

- `OverallQual`
- `GrLivArea`
- `GarageCars`
- `TotalBsmtSF`
- `1stFlrSF`
- `FullBath`
- `YearBuilt`

### 2. Mall Customers Dataset

The Mall Customers dataset is used for the clustering task.

Selected features:

- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

## Regression Model

A **Random Forest Regressor** was used to predict house sale prices.

The dataset was divided into:

- 80% training data
- 20% testing data

A `random_state` of 42 was used to make the results reproducible.

### Regression Results

| Metric | Result |
|---|---:|
| RMSE | 29,016.77 |
| R² Score | 0.8902 |

The R² score of approximately 0.8902 indicates that the model explains about 89.02% of the variation in house sale prices in the test set.

## Clustering

K-Means clustering was applied to the Mall Customers dataset.

Before clustering, the selected features were standardized using `StandardScaler` so that differences in feature scales would not disproportionately affect the clustering process.

### Elbow Method

The Elbow Method was used to compare inertia values for different numbers of clusters.

Based on the elbow curve, **4 clusters** were selected as a reasonable choice for the final K-Means model.

The resulting clusters were analyzed using average age, annual income, and spending score to understand the characteristics of different customer groups.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Project Structure

```text
vortextech-aiml-week3/
│
├── Regression_and_Clustering_Week3.ipynb
├── README.md
│
└── datasets/
    ├── train.csv
    └── Mall_Customers.csv
```

## How to Run

1. Install Python.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

3. Open the project folder in VS Code or Jupyter Notebook.
4. Make sure the datasets are available in the `datasets` folder, or update the file paths in the notebook if they are stored in the same directory.
5. Open:

```text
Regression_and_Clustering_Week3.ipynb
```

6. Run the notebook cells from top to bottom.

## Key Learning Outcomes

Through this project, I practiced:

- Data cleaning and preprocessing
- Feature selection
- Train/test splitting
- Random Forest Regression
- Regression evaluation
- RMSE and R² interpretation
- Feature scaling
- K-Means clustering
- Elbow Method
- Cluster visualization
- Real-world cluster interpretation

