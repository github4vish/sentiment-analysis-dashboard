# 📊 Sentiment Analysis Dashboard Project

### (Frontend + API Integration Assignment)

---

## 🎯 Project Title

**Design and Develop a Sentiment Analysis Intelligence Dashboard**

---

## 🧠 Project Objective

You are required to design and develop a **Sentiment Analysis Dashboard** based on a Machine Learning model built using:

* TF-IDF Vectorization
* Logistic Regression
* Text Preprocessing using NLTK
* Model Evaluation (Accuracy & Confusion Matrix)

The system must include:

1. Frontend Dashboard (UI)
2. Backend API Layer
3. Integration between Frontend and Backend

---

# 📁 Part 1: Given ML Script Overview

The backend model performs:

* Dataset loading (`reviews.csv`)
* Text preprocessing:

  * Lowercasing
  * Punctuation removal
  * Stopword removal
  * Stemming
* TF-IDF Feature Extraction
* Train-Test Split (80/20)
* Logistic Regression Training
* Model Evaluation
* Confusion Matrix Generation
* Live Sentiment Prediction

---

# 🖥️ Part 2: Dashboard Layout Design (Frontend)

You must design a responsive dashboard using:

* Bootstrap 5
* Chart.js (or similar)
* DataTables (for results table)
* Fetch API / Axios (for API calls)

---

## 📌 Required Dashboard Sections

---

## 1️⃣ Navbar

Include:

* Dashboard Title: **Sentiment Analysis Intelligence Dashboard**
* Upload Dataset Button
* Retrain Model Button
* Dark Mode Toggle
* User Dropdown

---

## 2️⃣ Dataset Overview Section

Display:

* Total Reviews
* Positive Reviews Count
* Negative Reviews Count
* Train/Test Split Ratio

### Chart:

* Doughnut Chart (Sentiment Distribution)

---

## 3️⃣ Text Preprocessing Visualization

Display NLP pipeline:

Original Text → Lowercase → Remove Punctuation → Remove Stopwords → Stemming

Include:

* Example transformation
* Side-by-side comparison

---

## 4️⃣ TF-IDF Feature Engineering Section

Display:

* Vocabulary Size
* Total Features
* Top 10 Important Words

### Chart:

* Bar chart showing top TF-IDF words

---

## 5️⃣ Model Training Summary

Display:

* Algorithm Used: Logistic Regression
* Train Size
* Test Size
* Random State

---

## 6️⃣ Evaluation Metrics Section

Display:

* Accuracy (Large numeric card)
* Precision
* Recall
* F1 Score

---

## 7️⃣ Confusion Matrix Section

Display a 2x2 matrix:

|                 | Predicted Negative | Predicted Positive |
| --------------- | ------------------ | ------------------ |
| Actual Negative | TN                 | FP                 |
| Actual Positive | FN                 | TP                 |

Use color-coded heatmap styling.

---

## 8️⃣ Live Sentiment Prediction Section

Include:

* Textarea input
* Analyze button
* Clear button

Display:

* Predicted Sentiment
* Confidence Score
* Color-coded result (Green = Positive, Red = Negative)

Optional:

* Sentiment Gauge Chart

---

## 9️⃣ Prediction Results Table

Table Columns:

* Review
* Actual Sentiment
* Predicted Sentiment
* Match (✔ / ✘)

Features:

* Pagination
* Search
* Filter by sentiment
* Download CSV option

---

# 🌐 Part 3: Backend API Endpoints

You must design REST APIs to support the dashboard.

---

## 🔹 System Endpoints

* `GET /api/health`
* `GET /api/model/info`

---

## 🔹 Dataset Endpoints

* `POST /api/dataset/upload`
* `GET /api/dataset/summary`
* `GET /api/dataset/sample`

---

## 🔹 Preprocessing Endpoints

* `POST /api/preprocess`
* `GET /api/preprocess/example`

---

## 🔹 Feature Engineering Endpoints

* `GET /api/features/summary`
* `GET /api/features/top-words`

---

## 🔹 Model Endpoints

* `POST /api/model/train`
* `GET /api/model/status`

---

## 🔹 Evaluation Endpoints

* `GET /api/model/metrics`
* `GET /api/model/confusion-matrix`
* `GET /api/model/classification-report`

---

## 🔹 Prediction Endpoints

* `POST /api/predict`
* `POST /api/predict/bulk`

---

## 🔹 Results Endpoints

* `GET /api/results`
* `GET /api/results/download`

---

# 🏗️ Part 4: System Architecture

You must implement:

Frontend (Bootstrap + JS)
⬇
Fetch API Calls
⬇
Flask Backend API
⬇
ML Model (TF-IDF + Logistic Regression)

---

# 📊 Part 5: Deliverables

Each student/group must submit:

1. Source Code (Frontend + Backend)
2. Screenshots of Dashboard
3. API Endpoint List
4. System Architecture Diagram
5. 2-page Project Report (PDF)
6. Demo Video (5–8 minutes)

---

# 🧪 Bonus Features (Optional for Extra Marks)

* ROC Curve Visualization
* Model Comparison (Add Naive Bayes)
* Word Cloud (Positive vs Negative)
* Dark Mode Implementation
* Authentication System
* Deploy on Render / Railway / Heroku

---

# 📝 Evaluation Criteria

| Criteria           | Marks   |
| ------------------ | ------- |
| UI Design & Layout | 15      |
| API Design         | 15      |
| Integration        | 15      |
| Visualization      | 15      |
| Code Quality       | 10      |
| Documentation      | 10      |
| Viva               | 20      |
| **Total**          | **100** |

---

# 📅 Submission Deadline

(To be announced by instructor)

---

# 🚀 Expected Learning Outcomes

After completing this project, students will understand:

* NLP preprocessing workflow
* TF-IDF feature extraction
* Logistic Regression classification
* REST API design
* Dashboard UI design
* Model evaluation metrics
* ML system integration

---

# ✅ Final Instruction

This project must demonstrate:

* Clear separation of frontend and backend
* Proper RESTful API design
* Interactive and responsive dashboard
* Accurate ML integration

---

**End of Assignment**
