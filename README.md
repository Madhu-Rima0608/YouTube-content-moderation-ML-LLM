# 🎯 YouTube Content Moderation System (ML vs LLM)

## 🚀 Project Overview

This project builds a **content moderation system** inspired by Trust & Safety challenges at platforms like YouTube.
It classifies user-generated comments into:

* **clean**
* **toxic**
* **severe_abuse**

The project compares **Machine Learning (ML)** and **Large Language Models (LLMs)** to understand trade-offs in **accuracy, scalability, and contextual understanding**.

---

## 🔐 Security Note

⚠️ API keys are **not included** in this repository.

To run the LLM section, set your API key as an environment variable:

```bash
setx GOOGLE_API_KEY "your_api_key_here"
```

Then restart your environment and run the notebook.

---

## 📌 Problem Statement

Online platforms must detect harmful content at scale while balancing:

* User safety
* Freedom of expression
* System performance

This project explores how ML and LLM approaches solve this problem differently.

---

## ⚙️ Approach

### 🔹 1. Data Processing

* Text cleaning and preprocessing
* Label consolidation into 3 categories
* Handling class imbalance

---

### 🔹 2. Machine Learning Model

* TF-IDF Vectorization
* Logistic Regression
* Class imbalance handling
* Threshold tuning

---

### 🔹 3. LLM-Based Classification

* Gemini API integration
* Prompt engineering
* Few-shot learning
* Output normalization

---

## 📊 Model Performance

### 🤖 Machine Learning Model

* High recall for toxic content
* Fast and scalable
* Limited contextual understanding

---

### 🧠 LLM Model

* ~93% accuracy (sample evaluation)
* Strong contextual understanding
* Better detection of nuanced abuse
* Slower and rate-limited

---

## 📈 Sample Results

| Comment           | Actual       | ML Prediction | LLM Prediction |
| ----------------- | ------------ | ------------- | -------------- |
| You are stupid    | toxic        | toxic         | toxic          |
| I love this video | clean        | clean         | clean          |
| I will kill you   | severe_abuse | toxic         | severe_abuse   |

---

## ⚖️ ML vs LLM Comparison

| Feature               | ML Model | LLM Model |
| --------------------- | -------- | --------- |
| Speed                 | Fast     | Slower    |
| Scalability           | High     | Limited   |
| Context Understanding | Moderate | Strong    |
| Consistency           | High     | Medium    |
| Cost                  | Low      | Higher    |

---

## 🔍 Key Insights

* LLMs improve detection of **contextual and implicit abuse**
* ML models are essential for **large-scale moderation systems**
* API-based models introduce **rate limits and latency constraints**
* A hybrid ML + LLM approach can significantly improve performance

---

## 🛠 Skills Demonstrated

* Python (Pandas, NumPy, Scikit-learn)
* NLP (TF-IDF, text preprocessing)
* Machine Learning (Logistic Regression)
* LLMs (Prompt Engineering, API Integration)
* Model Evaluation (Precision, Recall, F1-score)
* System Thinking (ML vs LLM tradeoffs)

---

## 📂 Repository Structure

* `youtube_content_moderation_ml_llm.ipynb` → Full implementation
* `README.md` → Documentation

---

## 👩‍💻 Author

**Madhurima Roy**
Aspiring Data Analyst | Data Storytelling | Social Impact

---
