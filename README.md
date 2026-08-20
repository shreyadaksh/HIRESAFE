# HIRESAFE

### Explainable AI-Powered Recruitment Scam Detection

> **Verify Before You Apply.**

HIRESAFE is a web-based system designed to help identify potentially fraudulent job postings and recruitment scams.

The system combines Natural Language Processing (NLP), lightweight Machine Learning, and rule-based risk indicators to analyse job postings and provide users with an explainable risk assessment.

---

## 🚨 Problem Statement

**Omni_CyberTech_10 — Identifying Fake Job Postings and Recruitment Scams**

Fake job postings and recruitment scams can deceive job seekers through misleading information, unrealistic offers, suspicious communication patterns, and fraudulent recruitment practices.

Students, fresh graduates, and inexperienced job seekers may find it difficult to identify these warning signs before interacting with a suspicious posting.

HIRESAFE aims to provide an accessible system that analyses job postings, identifies potentially suspicious characteristics, and explains the factors contributing to the detected risk.

---

## 💡 Proposed Solution

HIRESAFE allows users to submit a job posting for analysis.

The system processes the submitted content using NLP and Machine Learning techniques while also checking rule-based scam indicators.

The analysis provides:

- **Risk Score**
- **Risk Level**
- **Detected Red Flags**
- **Explanation of Suspicious Signals**
- **Safety Recommendations**

Instead of providing only a simple **"Fake" or "Genuine"** prediction, HIRESAFE focuses on an **explainable risk assessment** to help users understand why a job posting may be suspicious.

---

## 🔄 Core Workflow

```text
Job Posting
     ↓
Text Preprocessing
     ↓
NLP / TF-IDF Feature Extraction
     ↓
ML Classification
     +
Rule-Based Risk Analysis
     ↓
Risk Engine
     ↓
Risk Score & Risk Level
     ↓
Detected Red Flags
     ↓
Explanation & Safety Recommendation

---

##  Key Features

-  **Job Posting Analysis** — Analyse submitted job postings for suspicious characteristics.
-  **NLP & Machine Learning** — Use TF-IDF and lightweight ML classification.
-  **Risk Assessment** — Generate a risk score and risk level.
-  **Red Flag Detection** — Identify potentially suspicious patterns.
-  **Explainable Results** — Show why a posting may be considered risky.
-  **Safety Recommendations** — Provide guidance based on detected risk indicators.

---

##  Technology Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap

### Backend
- Python
- Flask

### Machine Learning & NLP
- Scikit-learn
- Pandas
- NumPy
- TF-IDF
- Lightweight ML Classification

### Database
- SQLite

### Development Tools
- VS Code
- Git
- GitHub

> HIRESAFE is designed around lightweight, CPU-friendly Machine Learning techniques and does not require a dedicated GPU or TensorFlow.

---

## 🤖 Machine Learning Approach

HIRESAFE uses a lightweight NLP and Machine Learning pipeline designed for CPU-based systems.

### Processing Pipeline

1. Collect and prepare job-posting data.
2. Clean and preprocess the text.
3. Convert text into numerical features using **TF-IDF**.
4. Train a lightweight classification model using **Scikit-learn**.
5. Evaluate the model using classification metrics.
6. Combine ML predictions with rule-based risk indicators.
7. Generate an explainable risk assessment.

The approach avoids GPU-intensive Deep Learning and is suitable for the available hardware.

---

## 🚩 Risk Analysis

HIRESAFE analyses multiple categories of suspicious signals.

### Content Signals
- Unrealistic offers
- Urgency-based language
- Suspicious wording
- Potentially misleading claims

### Contact Signals
- Unusual contact methods
- Suspicious email or domain patterns
- Inconsistent contact information

### Information Signals
- Missing company information
- Inconsistent job details
- Other potentially suspicious listing characteristics

These signals are combined with the ML output to generate the overall risk assessment.

---

## 📊 Model Evaluation

The Machine Learning component will be evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

The system will also be tested using realistic job-posting examples to assess detection quality, usability, and explainability.

---

## ✅ Feasibility

- **Software-only** — No specialized hardware required.
- **CPU-friendly** — Uses lightweight NLP and ML techniques.
- **Modular architecture** — Components can be improved independently.
- **Scalable** — Can be extended with additional models, rules, and data.
- **Practical development** — Suitable for standard computer systems.

---

## 🚀 Future Scope

- 🌍 **Multilingual Detection** — Support multiple languages.
- 🔌 **Browser Extension** — Analyse job postings while browsing.
- 📱 **Mobile Application** — Provide on-the-go scam detection.
- 🔗 **Platform API** — Integrate with recruitment platforms.
- 📊 **Advanced Scam Intelligence** — Expand the range of detected patterns.
- 🔄 **Continuous Updates** — Improve models and rules with new scam patterns.

---

## 📌 Project Status

**🚧 In Development**

HIRESAFE is currently under development as a proposed solution for the Omnikon National Hackathon 2026.

---

## 🏆 Hackathon Details

**Hackathon:** Omnikon National Hackathon 2026

**Theme:** Cybersecurity, Blockchain & Digital Trust

**Problem Statement:**  
**Omni_CyberTech_10 — Identifying Fake Job Postings and Recruitment Scams**

**Project:** HIRESAFE

**Tagline:**  
**Verify Before You Apply.**

---

## 🤝 AI Assistance

ChatGPT was used for brainstorming, solution structuring, technical planning, and content refinement.

---

## 📄 License

This project is currently being developed for the **Omnikon National Hackathon 2026**.
