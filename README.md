## 📰 **Fake News Detection with Machine Learning**
---
**Project Type:** Classification · Portfolio Project
**Target:** Classify news articles as *Fake* or *Real* using linguistic, social, and credibility-based features.

---

### ✅ **Problem Statement**

Misinformation spreads rapidly across digital platforms, eroding public trust, skewing perception, and threatening democratic processes. Developing an intelligent system to detect fake news is critical in safeguarding information integrity.

**Challenge:**
To accurately distinguish fake news articles from real ones using a multidimensional dataset that reflects real-world complexity.

---

### 🎯 **Objective**

To design and implement a machine learning pipeline that **predicts the authenticity of news articles** with **high precision and recall**, by combining metadata features and credibility signals.

---

### 📊 **Dataset Overview**

* **Size:** 4,000 articles
* **Sources:**

  * **Reliable:** e.g., *New York Times*, *BBC News*
  * **Misleading:** e.g., *The Onion*, clickbait websites
* **Features Include:**

  * `sentiment_score` (-1 to 1): Emotional tone
  * `word_count`: Article length
  * `num_shares`: Virality indicator
  * `trust_score`: Credibility level
  * `fact_check_rating`: 3rd-party verification score
  * `source_reputation`: Known history of source

---

### 🧠 **Approach & Techniques**

* **Preprocessing:** Text cleaning, tokenization, and normalization
* **Feature Engineering:** Combining content features (NLP) with metadata (credibility & social behavior)
* **Modeling:** Trained multiple classifiers including

  * Logistic Regression
  * Random Forest
  * Support Vector Machines (SVM)
* **Evaluation:** Precision, Recall, F1-score, ROC-AUC

> **Focus:** Prioritize models that **minimize false positives** (labeling real news as fake) while **maximizing true positives** (accurately catching fake news).

---

### 💡 **Why This Matters**

Unlike traditional models that rely solely on text, this project enhances detection by integrating *contextual credibility indicators* and *emotional tone*. This holistic approach reflects how real misinformation behaves—often emotionally charged, highly shared, and from questionable sources.

---

### 🧰 **Skills Demonstrated**

* **Sentiment Analysis & Feature Engineering**
* **Supervised Learning & Model Evaluation**
* **Interpretability for Misinformation Use Cases**

---

### 🧪 **Results & Impact**

* Achieved **\~92% accuracy** with ensemble models
* Noticed strong correlation between **low trust scores and extreme sentiment** in fake news
* Demonstrated how **metadata-driven insights** can outperform pure text-based classifiers
