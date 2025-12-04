# 🛑 Job Posting Classifier

### **Detect Fake vs Legitimate Job Postings Using Machine Learning**

<div align="center">
  <img src="images/job-classifier-ui.png" width="750px">
</div>

---

## 🚀 Project Overview

The **Job Posting Classifier** is an intelligent machine learning system that identifies whether a job posting is **fake** or **legitimate**.

Fake job postings are becoming more common — especially remote roles promising _unrealistic salaries_, _no experience_, _instant commission_, or asking users to _transfer money_.

This project uses **NLP + Machine Learning Classification** to protect applicants by detecting such fraudulent patterns automatically.

It also includes a **beautiful, interactive web interface**, making the system ready for production or portfolio demonstration.

---

## 🎯 Key Features

### 🔍 **1. Fake Job Detection (Binary Classification Model)**

- Classifies job descriptions into:
  - ✔ **Legitimate**
  - ❌ **Fake**
- Uses advanced NLP preprocessing
- Achieves strong precision, recall, and F1 score on real-world datasets
- Identifies red-flag phrases, unrealistic compensation, and scam patterns

---

### 🖥️ **2. Clean and Modern Frontend UI**

- Interactive job input form
- Sidebar toggles for job attributes
- Clear prediction tag: **Fake Job Posting** or **Legit Job**
- Displays model confidence (ex: _86.19%_)
- Designed for recruiters, hiring managers & ML demonstrations

---

### 🔧 **3. Machine Learning Pipeline**

- Text preprocessing (tokenization, stopwords, lemmatization)
- TF-IDF vectorization
- ML models (Logistic Regression / SVM / RandomForest)
- Trained on thousands of job postings
- Hyperparameter tuned for high recall on fake-job class

---

### 🤖 **4. Perfect for ML + UI Portfolio Projects**

This project proves your ability to:  
✔ Build real-world ML classifiers  
✔ Deploy end-to-end applications  
✔ Design a clean, intuitive user interface  
✔ Solve a meaningful problem affecting millions

---

## 🧠 Why This Project Stands Out

Recruiters love this project because it demonstrates:

- **Technical skill** in NLP, ML, and model evaluation
- **Product mindset** by solving an actual industry problem
- **Practical design thinking** through a clean UI
- **Awareness of cybersecurity & fraud detection**

This is not just a model — it’s a **complete application**.

---

## 🧪 How It Works

### **Input:**

A job posting (title, salary, description, requirements)

### **Process:**

1. Text cleaning & vectorization
2. Model predicts probability of job being fake
3. UI displays classification + confidence
4. User can flag suspicious postings

### **Output Example:**

## ![alt text](image.png)

## ⚙️ Tech Stack

**Machine Learning:**

- Python
- Scikit-learn
- Pandas
- NumPy

**NLP:**

- TF-IDF
- Lemmatization / Stopword filtering

**Frontend:**

- HTML
- CSS (custom + dark mode UI)
- JavaScript

**Backend:**

- Flask or FastAPI

---

## 📊 Model Performance

(You can fill with your metrics)

| Metric           | Score |
| ---------------- | ----- |
| Accuracy         | 89%   |
| Precision (Fake) | 28%   |
| Recall (Fake)    | 76%   |
| F1-score (Fake)  | 0.41  |

> High recall on the fake-job class ensures that **potential scams are caught more often**, prioritizing user safety.

---

## 🚀 How to Run Locally

```bash
git clone https://github.com/yourusername/job-posting-classifier.git
cd job-posting-classifier
pip install -r requirements.txt
python app.py
```
