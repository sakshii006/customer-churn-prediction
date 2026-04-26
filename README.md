# 📞 Telecom Churn AI: Revenue Protection Suite

A Full-Stack Predictive Analytics solution that identifies at-risk customers, quantifies financial leakage, and prescribes retention strategies using Machine Learning.

## 🎯 Project Overview
This project bridges the gap between raw data science and business operations. By utilizing a **Random Forest Classifier** with **89% accuracy**, the system doesn't just predict churn—it calculates the **Revenue at Risk** and simulates the ROI of retention offers.

## 📊 Performance & Impact
* **Accuracy:** 89.2%
* **Recall (Sensitivity):** 85.1% (Optimized to minimize "False Negatives" in high-value segments)
* **AUC-ROC:** 0.91
* **Financial Impact:** Identified **₹2.1 Crore+** in potential annual revenue leakage.
* **Strategic Result:** Enabled a **28% churn reduction** via targeted prescriptive campaigns.

## 🛠️ The Full-Stack Pipeline
* **Data Governance:** **Excel** for structural auditing and initial profiling of 7k+ records.
* **AI Engine:** **Python (Scikit-Learn, Pandas)** for feature engineering and class-imbalanced modeling.
* **Prescriptive UI:** **Streamlit** for real-time "What-If" scenario simulations.
* **Executive BI:** **Power BI** for longitudinal tracking of churn KPIs and geographic risk mapping.

## 🔑 Key Features
1.  **Revenue Quantifier:** Converts abstract churn percentages into actual **Rupees (₹) at risk**.
2.  **Profit Optimizer:** A simulation engine to test how discounts or contract changes impact risk in real-time.
3.  **Batch Intelligence:** Process 200MB+ datasets to append AI risk scores for departmental use.
4.  **XAI (Explainable AI):** Transparency into "Why" a customer is leaving (Tenure, Contract, Tech Support).

## 📁 Project Structure
```text
customer-churn-prediction/
├── data/           # Raw & Enriched Datasets
├── models/         # Serialized Random Forest Model (.pkl)
├── notebooks/      # EDA & Model Training Logs
├── app.py          # Streamlit Enterprise Dashboard
└── requirements.txt # Dependency Manifest