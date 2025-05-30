# Naive Bayes Classifier for Fake News Recognition
**Fake news** is defined by *The New York Times* as "a made-up story with an intention to deceive", with the intent to confuse or deceive people. Fake news is widespread in our daily lives, particularly on social media platforms and applications. Being able to distinguish fake content from real news is one of the most serious challenges facing the news industry today.

Naive Bayes classifiers \[1] are powerful algorithms used for text data analysis, particularly in text classification tasks. The goal of this project is to implement a **Multinomial Naive Bayes classifier** in Python and evaluate its performance in classifying social media posts.

The suggested dataset is available on Kaggle \[2]. Possible suggested labels for classifying the text are:

* **True** - 5
* **Not-Known** - 4
* **Mostly-True** - 3
* **Half-True** - 2
* **False** - 1
* **Barely-True** - 0

The Kaggle dataset \[2] consists of:

* **Training set**: 10,240 instances
* **Test set**: 1,267 instances

## Project Tasks

1. **Divide the dataset** into training, validation, and testing sets
2. **Tokenize** each word (convert uppercase to lowercase, then split into tokens)
3. **Clean the data** by removing stop words
4. **Perform token normalization**: create equivalence classes to map similar tokens to the same class
5. **Build the vocabulary** and perform **feature selection**
6. **Train and evaluate** the Naive Bayes classifier
7. **Show the results** using appropriate metrics and visualizations

## Additional Task

Apply the developed methods and techniques to a second dataset \[3], which is a binary classification task with the following labels:

* **1** $\rightarrow$ *Unreliable*
* **0** $\rightarrow$ *Reliable*

## Final Goal

Compare and analyze the performance of the Naive Bayes classifier on the two datasets and draw conclusions from the results.

---

### Bibliography

\[1] C. D. Manning, *Chapter 13, Text Classification and Naive Bayes*, in *Introduction to Information Retrieval*, Cambridge University Press, 2008.

\[2] [Fake News Content Detection Dataset – Kaggle](https://www.kaggle.com/datasets/anmolkumar/fake-news-content-detection?select=train.csv)

\[3] [Fake News Classification(build a system to identify unreliable news articles) – Kaggle Competition](https://www.kaggle.com/competitions/fake-news/data?select=train.csv)

---
