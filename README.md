# 🎬 Movie Review Sentiment Analysis

This project focuses on analyzing movie reviews and classifying them as **positive** or **negative** using machine learning techniques.

---

## Overview
The aim of this project is to build a model capable of understanding the sentiment behind a text review. By preprocessing textual data and training a machine learning model, we can predict whether a review reflects a positive or negative opinion about a movie.

---

## Dataset
- **Source:** IMDb Movie Review Dataset  : https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
- **Size:** 50,000 reviews (balanced between positive and negative)
- **Features:** Review text, sentiment label (0 = Negative, 1 = Positive)

---

## Methodology
1. **Data Preprocessing:**  
   - Tokenization, stopword removal, and lemmatization.  
   - Text vectorization using TF-IDF.

2. **Model Training:**  
   - Logistic Regression / Naive Bayes (tested for accuracy).  
   - Evaluated using metrics like accuracy, precision, and recall.

3. **Implementation Tools:**  
   - Python, Pandas, Scikit-learn, NLTK, Matplotlib.

---

## Results
- Achieved around **88–90% accuracy** on the test dataset.  
- Logistic Regression performed best in balancing accuracy and interpretability.

---

## Future Work
- Extend to multi-class classification (e.g., neutral sentiment).  
- Integrate deep learning (LSTM or BERT).  
- Deploy as a simple web app for live sentiment prediction.

---
