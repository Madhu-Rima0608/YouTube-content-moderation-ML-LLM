# 🛡️ AI-Powered Trust & Safety Monitoring System

## 🚀 Project Overview
This project builds a content moderation system inspired by Trust & Safety challenges at platforms like YouTube. It classifies user-generated comments into:

- clean  
- toxic  
- severe_abuse  

The project compares **Machine Learning (ML)** and **Large Language Models (LLMs)** to understand trade-offs in **accuracy, scalability, and contextual understanding**.

To make moderation insights more actionable, the project also includes an interactive **Power BI Trust & Safety Dashboard** for monitoring harmful content trends, moderation effectiveness, and AI model performance.

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

- User safety  
- Freedom of expression  
- System performance  

This project explores how **ML and LLM approaches** solve this problem differently.

---

## ⚙️ Approach

### 🔹 1. Data Processing
- Text cleaning and preprocessing  
- Label consolidation into 3 categories  
- Handling class imbalance  

### 🔹 2. Machine Learning Model
- TF-IDF Vectorization  
- Logistic Regression  
- Class imbalance handling  
- Threshold tuning  

### 🔹 3. LLM-Based Classification
- Gemini API integration  
- Prompt engineering  
- Few-shot learning  
- Output normalization  

### 🔹 4. Trust & Safety Dashboard
- Harmful content monitoring  
- Moderation effectiveness tracking  
- Repeat offender analysis  
- AI model performance evaluation  

---

## 📊 Model Performance

### 🤖 Machine Learning Model
- High recall for toxic content  
- Fast and scalable  
- Limited contextual understanding  

### 🧠 LLM Model
- ~93% accuracy (sample evaluation)  
- Strong contextual understanding  
- Better detection of nuanced abuse  
- Slower and rate-limited  

---

## 📈 Sample Results

| Comment | Actual | ML Prediction | LLM Prediction |
|----------|---------|----------------|----------------|
| You are stupid | toxic | toxic | toxic |
| I love this video | clean | clean | clean |
| I will kill you | severe_abuse | toxic | severe_abuse |

---

## ⚖️ ML vs LLM Comparison

| Feature | ML Model | LLM Model |
|----------|-----------|------------|
| Speed | Fast | Slower |
| Scalability | High | Limited |
| Context Understanding | Moderate | Strong |
| Consistency | High | Medium |
| Cost | Low | Higher |

---

## 📊 Trust & Safety Dashboard

To move beyond model predictions and generate actionable insights, I developed an interactive **Power BI dashboard** for monitoring harmful content and moderation performance.

### 🏠 Executive Overview
- Total content monitored  
- Toxic content trends over time  
- Content moderation breakdown  
- High-risk region analysis  

### ⚠️ Risk Analysis
- Most reported harmful comments  
- Repeat offender tracking  
- High-risk content monitoring  

### 🛡️ Moderation Efficiency
- Allowed vs removed content  
- Moderation trends over time  
- AI misclassification analysis  

### 🤖 AI Performance
- Correct vs incorrect predictions  
- Model accuracy tracking  
- Prediction trend analysis  

---

## 📸 Dashboard Preview

### Home Page
<img width="1305" height="782" alt="image" src="https://github.com/user-attachments/assets/c9c2acc2-3fc6-49eb-8088-6697aa30c376" />


### Executive Overview
<img width="1490" height="742" alt="image" src="https://github.com/user-attachments/assets/327e40bf-fa6c-4f1a-8d29-fe217888afe7" />


### Risk Analysis
<img width="1321" height="741" alt="image" src="https://github.com/user-attachments/assets/9e498fd5-feb7-4700-875e-0e67fb393c46" />


### Moderation Efficiency
<img width="1326" height="737" alt="image" src="https://github.com/user-attachments/assets/3ea83d44-8b79-47d6-bfd2-1e38bdd3828e" />


### AI Performance
<img width="1332" height="750" alt="image" src="https://github.com/user-attachments/assets/aa1f6b38-3c1b-4ded-a16d-203a6670bbb2" />


---

## 🔍 Key Insights

- LLMs improve detection of contextual and implicit abuse  
- ML models are essential for large-scale moderation systems  
- API-based models introduce rate limits and latency constraints  
- A hybrid **ML + LLM** approach can significantly improve performance  
- Interactive dashboarding transforms moderation outputs into actionable **Trust & Safety insights**

---

## 🛠 Skills Demonstrated

- Python (Pandas, NumPy, Scikit-learn)  
- NLP (TF-IDF, text preprocessing)  
- Machine Learning (Logistic Regression)  
- LLMs (Prompt Engineering, API Integration)  
- Power BI & DAX  
- Data Visualization & Dashboard Storytelling  
- Model Evaluation (Precision, Recall, F1-score)  
- System Thinking (ML vs LLM trade-offs)  
- Trust & Safety Analytics  

---

## 👩‍💻 Author

**Madhurima Roy**  

Data Analyst | Data Storytelling | Social Impact
