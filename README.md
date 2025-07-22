# Document-Clustering-for-Topic-Modeling
# 🧠 Topic Modeling on 20 Newsgroups Dataset using LDA, KMeans, and NMF

This project explores Topic Modeling techniques using **LDA**, **KMeans**, and **NMF** on the **20 Newsgroups Dataset**. It includes comprehensive preprocessing, multiple clustering algorithms, topic evaluation metrics, and intuitive visualizations.

# 📄 Document-Clustering-for-Topic-Modeling  
## 🧠 Topic Modeling on 20 Newsgroups Dataset using LDA, KMeans, and NMF

This project explores Topic Modeling techniques using **LDA**, **KMeans**, and **NMF** on the **20 Newsgroups Dataset**. It includes comprehensive preprocessing, multiple clustering algorithms, topic evaluation metrics, and intuitive visualizations.

---

## 📌 Project Objectives

- Clean and preprocess raw text data.
- Convert documents to TF-IDF vectors.
- Apply **KMeans Clustering** to group documents.
- Explore **LDA** and **NMF** for probabilistic topic modeling.
- Identify topics from clusters using top keywords.
- Visualize topics using **WordClouds** and plots.

---

## 🧾 Dataset

We use the **20 Newsgroups Dataset**, a collection of ~18,000 newsgroup posts across 20 categories.

- Source: `sklearn.datasets.fetch_20newsgroups`
- Categories include: politics, religion, sports, computers, science, etc.
- Widely used for NLP tasks such as text classification, topic modeling, and clustering.

---

## 🧠 Topic Modeling Techniques Used

This project implements and compares the following techniques:

- **LDA (Latent Dirichlet Allocation)**: A generative model where each document is a mixture of topics.
- **NMF (Non-negative Matrix Factorization)**: Matrix factorization that uncovers latent topics based on non-negativity.
- **KMeans Clustering**: Distance-based document clustering followed by keyword-based topic extraction.

---

## 🛠️ Technologies & Libraries

- Python 3.x
- Jupyter Notebook
- Libraries used:
  - `pandas`, `numpy`
  - `nltk`, `scikit-learn`
  - `matplotlib`, `seaborn`
  - `wordcloud`

---

## 🚀 Workflow Overview

1. **Load Data**: Import documents from 20 Newsgroups.
2. **Text Preprocessing**:
   - Lowercasing
   - Stopword removal
   - Tokenization
   - Lemmatization
3. **Feature Extraction**:
   - Convert documents into TF-IDF matrix
4. **Clustering & Topic Modeling**:
   - KMeans: Cluster documents into similar groups
   - LDA & NMF: Extract latent topics
5. **Visualization**:
   - Elbow curve to determine optimal `k`
   - WordClouds and top keywords for each topic

---

## 📊 Output & Visualizations

- Cluster Assignments per Document
- WordClouds for Each Topic
- Top Terms per Cluster
- Elbow Curve Plot for Optimal K
- Topic-wise document distribution

---

## 📁 Project Structure

Developed by **Saloni Saini**  
📧 saloniskr2003@gmail.com  
🔗 [GitHub Profile](https://github.com/SaloniSsSaini)



