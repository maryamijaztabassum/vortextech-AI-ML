# Sentiment Analysis Model using IMDB Movie Reviews

**Vortex Tech AI & ML Internship -- Week 4 (Capstone Project)**

## Project Overview

This project is the final capstone task of the **Vortex Tech AI & ML
Internship Program 2026**. The goal was to build a **Sentiment Analysis
Model** that classifies movie reviews as **Positive** or **Negative**
using Natural Language Processing (NLP) techniques.

The model was trained on the **IMDB Movie Reviews** dataset containing
**50,000 labeled reviews** and achieved approximately **88.73%
accuracy** on the test data.

------------------------------------------------------------------------

## Dataset

-   **Dataset:** IMDB Dataset of 50K Movie Reviews
-   **Source:** Kaggle
-   **Size:** 50,000 movie reviews
-   **Classes:** Positive and Negative

Dataset Link:
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

------------------------------------------------------------------------

## Project Workflow

The project follows a complete NLP pipeline:

1.  Loaded the IMDB Movie Reviews dataset.
2.  Explored the dataset and checked class balance.
3.  Cleaned the text by:
    -   Converting text to lowercase
    -   Removing punctuation and special characters
    -   Removing English stopwords
4.  Converted text into numerical features using **TF-IDF
    Vectorization**.
5.  Split the data into **80% training** and **20% testing** sets.
6.  Trained a **Logistic Regression** classifier.
7.  Evaluated the model using Accuracy, F1-score, Classification Report,
    and Confusion Matrix.
8.  Tested the trained model on three custom sentences.

------------------------------------------------------------------------

## Technologies Used

-   Python
-   Pandas
-   NumPy
-   Scikit-learn
-   NLTK
-   Matplotlib

------------------------------------------------------------------------

## Model Performance

  Metric     Result
  ---------- ------------------------
  Accuracy   **88.73%**
  F1-Score   **≈88.9%**
  Model      Logistic Regression
  Features   TF-IDF (5000 features)

### Confusion Matrix Results

-   True Negatives: **4332**
-   False Positives: **629**
-   False Negatives: **498**
-   True Positives: **4541**

------------------------------------------------------------------------

## Custom Predictions

The model was tested on three new sentences:

  Sentence                                                   Prediction
  ---------------------------------------------------------- ------------
  This was the best experience ever. I loved every moment.   Positive
  This movie was a complete waste of time.                   Negative
  The acting was decent but the story became boring.         Negative

------------------------------------------------------------------------

## Project Structure

    vortextech-aiml-week4/
    │── Sentiment_Analysis_Model.ipynb
    │── README.md
    └── IMDB Dataset.csv

------------------------------------------------------------------------

## How to Run

1.  Clone or download this repository.
2.  Install the required libraries.

``` bash
pip install pandas numpy scikit-learn nltk matplotlib
```

3.  Place **IMDB Dataset.csv** in the project folder.
4.  Open `Sentiment_Analysis_Model.ipynb`.
5.  Run all notebook cells.

------------------------------------------------------------------------

## Limitations

The model performs well on movie reviews but may struggle with sarcasm,
irony, and mixed emotions because TF-IDF focuses on word importance
rather than deep contextual understanding.

------------------------------------------------------------------------

## Author

**Maryam Ijaz**

**Vortex Tech AI & ML Internship Program 2026**
