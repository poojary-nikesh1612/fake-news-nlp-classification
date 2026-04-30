# Fake News Detection using NLP

This project classifies news articles as **Fake** or **Real** using classical Natural Language Processing (NLP) techniques.

---

## Techniques Used

- Text Preprocessing (stopword removal, punctuation removal, lemmatization)
- Bag of n-grams (Unigram + Bigram)
- Machine Learning Models:
  - Multinomial Naive Bayes
  - Random Forest Classifier

---

## Results

Both models performed well, with **Random Forest** achieving slightly better performance than Naive Bayes in terms of accuracy and F1-score.

---

## Dataset

- Source: [Kaggle Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

---

## Tools & Libraries

- Python  
- Pandas  
- Scikit-learn  
- spaCy  

---

## How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/poojary-nikesh1612/fake-news-nlp-classification.git
   ```

2. Navigate to the project folder:
   ```bash
   cd fake-news-nlp-classification
   ```

3. Install required libraries:
   ```bash
   pip install pandas scikit-learn spacy
   ```

4. Download spaCy model:
   ```bash
   python -m spacy download en_core_web_sm
   ```

5. Open the notebook:
   - Run the `.ipynb` file using Jupyter Notebook or Google Colab

6. Run all cells to:
   - Preprocess text
   - Train models
   - Evaluate results

---
