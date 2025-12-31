👉 For a quick, no-setup review of full analysis, see `operator_performance_analysis_telecom.html`.  
👉 Interactive Tableau dashboard:
<ul style="font-size:14px; line-height:1.8">
  <li>
    📊 <strong><a href="https://public.tableau.com/views/Sprit_15TableauDashboard/Sprint15Dashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" target="_blank">
    Interactive Tableau Dashboard</a></strong>  
    <br><span style="color:darkgray">
    Explore key operational insights through dynamic filters and performance metrics.
    </span>
  </li>
</ul>

## Executive Summary

This project evaluates call center operator performance to identify inefficiencies using objective, data-driven metrics.  
Operators were classified as **efficient**, **inefficient**, or **borderline** based on waiting times, missed conversations, and outbound activity.

Statistical validation confirmed that inefficient operators consistently exhibit **longer waiting times, higher abandonment rates, and lower outbound activity**, with all key differences statistically significant (p < 0.05).

The results support a scalable monitoring framework that enables **early intervention, targeted coaching, and continuous performance tracking**, reducing reliance on subjective evaluation.

---

# Operator Performance Analysis — Applied Analytics

End-to-end operational analytics project to **identify underperforming call center operators** using data validation, behavioral metrics, and statistical testing, with results delivered through an interactive Tableau dashboard.

---

## Business Problem
Call center supervisors need an objective way to detect **inefficient operators** before service quality degrades.  
This project builds a **data-driven monitoring system** to flag inefficient and borderline operators based on waiting times, missed conversations, and outbound activity.

---

## Dataset
Telecommunications event data including:
- Incoming, outgoing, and internal conversations  
- Call durations and waiting times  
- Operator assignments and customer accounts  

Each row represents a **conversation**, not an individual call.

---

## Analytical Approach
- Robust preprocessing & validation (logical checks, duplicates, outliers)
- Feature engineering to create operator-level performance metrics
- Behavioral segmentation (efficient, inefficient, borderline)
- Rule-based classification using percentiles and operational logic
- Statistical validation using **Mann–Whitney U tests**
- Interactive visualization with **Plotly (Python)** and **Tableau**

---

## Key Results
- Identified **inefficient operators** with significantly higher waiting times and missed conversations
- Detected **borderline operators** requiring monitoring before performance deterioration
- For outbound operators, confirmed **significantly lower activity levels**
- All differences were **statistically significant (p < 0.05)**

---

## Business Impact
- Enables **early intervention** for underperforming operators
- Replaces subjective evaluation with **metric-driven monitoring**
- Scales to continuous operational performance tracking

---

## Deliverables
- **Jupyter Notebook (`.ipynb`)** — full reproducible analysis
- **Tableau Dashboard** — interactive performance monitoring tool

### 📊 Interactive Visualizations (Plotly)

This project includes **interactive Plotly visualizations** that allow deeper exploration of operator performance across metrics and groups.

1. Download the file **`operator_performance_analysis_telecom.html`**
2. Open it locally in any modern web browser (Chrome, Firefox, Safari).

> ⚠️ GitHub does not render Plotly interactivity inside notebooks or HTML previews.  
> For full interactivity (dropdowns, tooltips, dynamic filtering), the HTML file must be opened locally.

These visualizations complement the Tableau dashboard by enabling **operator-level and metric-level exploration** directly from the analysis notebook.

---

## Validation
This project underwent a **final analytical review**, validating:
- Metric definitions and logic
- Statistical test selection and interpretation
- Consistency between analysis, conclusions, and visualizations

---

## Notes
Completed as the **final capstone-style sprint** of the TripleTen Data Analytics Bootcamp, simulating a real-world operational analytics use case.