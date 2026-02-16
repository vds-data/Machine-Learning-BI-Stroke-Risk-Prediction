
# 🧠 Machine Learning & Business Intelligence for Stroke Risk Prediction
Machine Learning and Business Intelligence project using Weka to predict stroke risk and translate health analytics into business KPIs, ROI, and strategic insights for a hypothetical cryonics company.

## 📌 Overview
Using a public stroke-prediction dataset, this project builds, evaluates, and interprets predictive models to identify **high-risk health patterns** and translate them into **actionable business insights**.

The case study is framed around a **hypothetical cryonics company**, demonstrating how predictive health analytics can support **preventive services, digital health initiatives, and long-term Business Intelligence (BI) strategy**, even in the absence of internal patient data.

---

## 🎯 Project Objectives
- Apply machine learning models to predict stroke risk  
- Handle real-world data challenges (missing values, class imbalance)  
- Compare and evaluate multiple ML algorithms  
- Discover hidden patterns through clustering  
- Translate ML outputs into business KPIs and ROI  
- Demonstrate how analytics supports strategic decision-making  

---

## 📊 Dataset
- **Source:** Public Stroke Prediction Dataset (Kaggle)  
- **Size:** 5,109 records  
- **Target Variable:** Stroke (Yes / No)  
- **Key Features:**  
  - Age  
  - Gender  
  - Hypertension  
  - Heart disease  
  - Average glucose level  
  - BMI  
  - Smoking status  

---

## 🧹 Data Preparation & Feature Engineering
- Missing BMI values replaced with mean values (~3.9% of data)  
- Smoking status *“unknown”* retained as a separate category  
- Continuous variables transformed into **clinically meaningful categories**  
- Age, BMI, and glucose grouped into medically relevant risk ranges  
- Significant class imbalance addressed using **undersampling**  
- Final balanced dataset used for model training and evaluation  

---

## 🤖 Machine Learning Methodology
This project applies both **supervised and unsupervised machine learning** techniques using **Weka**.

### Supervised Learning (Classification)
- J48 Decision Tree  
- Naive Bayes  
- Random Forest  

**Model Evaluation Metrics:**
- Accuracy  
- Precision  
- F-Measure  
- Paired T-Test comparisons  

➡️ **J48** was selected as the final model due to its strong performance and high interpretability.  

**Best Accuracy Achieved:** **76.84%**

---

### Unsupervised Learning (Clustering)
- **K-Means Clustering**

Used to:
- Identify shared health-risk profiles  
- Support segmentation and pattern discovery  
- Enhance interpretability of risk groups  

---

## 🔍 Feature Combination Analysis
Multiple combinations of health attributes were evaluated to optimize prediction performance.

**Key findings:**
- **Age** is the most critical predictor across all models  
- **Hypertension, BMI, glucose levels, and smoking status** significantly improve model interpretability  
- Simple, well-chosen feature sets can outperform more complex models  

---

## 📈 Business Intelligence & KPIs
Machine-learning outputs were translated into **business-oriented metrics**, including:
- Prediction accuracy and reliability  
- Identification speed of high-risk individuals  
- Adoption rate of preventive health services  
- Revenue from analytics-driven services  
- **Return on Investment (ROI)**  

Interactive dashboards were designed to simulate **real-world BI reporting** and executive decision support.

---

## 💰 ROI Analysis (Hypothetical Scenario)
- **Total BI-Driven Revenue (2024–2025):** €1,293,098  
- **Total BI Investment Cost:** €218,380  
- **ROI:** **4.92**

This demonstrates the **strategic and financial value** of integrating Machine Learning with Business Intelligence.

---

## 🛠️ Tools & Technologies
- **Machine Learning:** Weka (J48, Naive Bayes, Random Forest, K-Means)  
- **Data Processing:** Excel  
- **Business Intelligence & Visualization:** Tableau  
- **Techniques:**  
  - Predictive modeling  
  - Clustering  
  - KPI tracking  
  - ROI analysis  

---

## 🧩 Key Insights
- Machine Learning enables early identification of high-risk health profiles  
- Interpretable models are critical for business and healthcare contexts  
- BI bridges the gap between technical predictions and strategic decisions  
- Predictive analytics can drive preventive services and long-term growth  

---

## 📚 Academic Context
This project was developed as part of **CSYM505 – Business Intelligence & Data Analytics** and follows best practices in:
- Machine learning evaluation  
- Data governance  
- BI strategy alignment  
- Ethical handling of health-related data  

---

## 👩‍💻 Author
**Vasileia Damaskou Sutton**  
MSc Business Information Systems & Data Analytics  
GitHub: `vds-data`  
LinkedIn: *(add your link)*  
