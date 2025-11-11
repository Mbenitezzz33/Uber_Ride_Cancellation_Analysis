# Uber Ride Cancellation Analysis 🚕📊

This project analyzes ride cancellation behavior using Uber trip data.  
We clean, model, and segment riders into **risk bands** using a Random Forest classifier, then visualize cancellation patterns in an **interactive Power BI dashboard**.

---

## 📌 Objectives

- Understand factors that drive ride cancellations.
- Predict the probability that a ride will be cancelled **before pickup**.
- Segment riders into **Low / Medium / High Risk** groups.
- Provide an intuitive dashboard for operational insights.

---

## 🧠 Data Science Workflow

| Step | Description |
|-----|-------------|
| Data Cleaning | Removed leak-prone fields & handled missing values |
| Feature Engineering | Time-based cyclical encoding (hour_sin / hour_cos), ride behavior aggregates |
| Model | Random Forest Classifier with balanced training |
| Risk Segmentation | Converts predicted probability → Low, Medium, High risk bands |
| Exports | Cleaned dataset + risk scores to use in Power BI |

---

## 🔍 Key Insights

- **Waiting Time is the strongest predictor** of cancellation behavior.
- Cancellations are **more likely in evening peak hours (5–8 PM)**.
- High-risk riders frequently show **longer wait times and inconsistent ride history** patterns.
- The **High-risk segment shows ~70–80% cancellation probability**, while low-risk is typically < 25%.

---

## 📈 Power BI Dashboard

The dashboard includes:

- **Gauge** showing average cancellation probability by risk segment
- **Risk-band slicer** to interactively filter across visuals
- **Time-of-day heatmap** to identify peak cancellation windows
- **Feature importance bar chart** showing strongest predictors




---



