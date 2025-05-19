# Movie Success Prediction & Sentiment Analysis

This project predicts movie success using IMDB data and analyzes viewer sentiments from movie overviews.  
We use Python, NLTK (VADER), and machine learning models to gain insights into what makes a movie successful!

---

## Project Overview

- **Dataset:** `imdb_top_1000.csv`
- **Objective:**  
  - Predict the success of movies based on key features.
  - Analyze genre-wise sentiment trends from movie overviews.

---

##  Tools and Libraries

- Python 3
- Pandas, Numpy
- Matplotlib, Seaborn
- Scikit-Learn
- NLTK (VADER Sentiment Analysis)

---

## Key Features Used for Prediction

- `Gross Revenue`
- `IMDB Rating`
- `No of Votes`

---

## Project Workflow

1. **Data Preprocessing:**  
   - Cleaned missing values
   - Handled numerical transformations
   - Created a custom `Success` label based on rating and revenue

2. **Sentiment Analysis:**  
   - Performed sentiment scoring on `Overview` text using VADER
   - Analyzed genre-wise average sentiment

3. **Model Building:**  
   - Trained a **Random Forest Classifier** using only key features
   - Achieved prediction accuracy and performance reports

4. **Visualizations:**  
   - Genre vs Average Sentiment Bar Plot
   - IMDB Rating vs Gross Revenue Scatter Plot
   - Feature Importance Plot

---

## Results

- **Most important features:** `Gross Revenue`, `IMDB Rating`, and `No of Votes`
- **Sentiment Trends:**  
  Some genres like *Drama* and *Action* tend to have more positive overview sentiments.
- **Model Accuracy:**  
  > Accuracy score : 1.0
