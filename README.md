# Real-World Industry Projects

A collection of end-to-end data science, econometrics, and machine learning projects applying predictive modeling, causal inference, and risk analytics to solve complex industry problems.

---

## Portfolio Projects

### 1. Personal Financial Risk & Stress Prediction Engine
* **Domain:** Personal Finance & FinTech
* **Focus:** Modeling individual credit risk, financial stress indicators, and default probabilities to support automated underwriting and personalized risk management.
* **Key Results:**
  * Cleaned and engineered financial feature pipelines incorporating debt-to-income ratios and payment history behaviors.
  * Implemented machine learning classification algorithms to stratify individuals into action-oriented financial risk tiers.

### 2. Optimizing Clinic Attendance with Machine Learning
* **Domain:** Healthcare Operations
* **Focus:** Predicting patient appointment no-shows and designing operational risk stratification frameworks to reduce clinic idle time.
* **Key Results:**
  * Identified scheduling lead time as the main driver of absenteeism (15.8 days for no-shows vs. 8.8 days for attended).
  * Built a predictive classifier isolating a High-Risk patient cohort with a 73.1% actual no-show rate.
  * Formulated dynamic overbooking and interactive 2-way outreach strategies.

### 3. Predictive Modeling of Hotel Cancellations & Revenue Optimization
* **Domain:** Hospitality & Revenue Management
* **Focus:** Forecasting reservation cancellation risks, evaluating revenue exposure, and mitigating unfulfilled room inventory through machine learning.
* **Key Results:**
  * Quantified booking lead time as a primary risk vector, with cancellations exceeding 45% for bookings made >90 days in advance.
  * Built a LightGBM classification pipeline achieving high discriminatory power ($\text{ROC-AUC} \approx 0.88+$) at the time of reservation.
  * Designed operational strategies including tiered advance deposits, pre-arrival engagement triggers, and dynamic overbooking buffers.

### 4. Flight Delay Prediction & Operational Risk Analytics
* **Domain:** Aviation & Airline Operations
* **Focus:** Quantifying operational delay drivers, analyzing network propagation, and predicting flight arrival delays ($>15$ minutes) across 5.7M flights.
* **Key Results:**
  * Revealed strong carrier performance variance (Hawaiian/Alaska at 10–12% vs. Spirit/Frontier at 25–29%) and late-day delay escalation (>25% past 18:00).
  * Isolated `LATE AIRCRAFT` (24.2 min) and `AIRLINE` control (19.6 min) as the primary operational drivers over weather disruptions (3.0 min).
  * Developed a LightGBM classifier ($\text{ROC-AUC} = 0.7114$) and established probability threshold optimization strategies for imbalanced class detection.

---

## Repository Structure

```text
.
├── Finance_Personal_Financial_Risk_&_Stress_Prediction_Engine.ipynb
├── Health_Optimizing_Clinic_Attendance.ipynb
├── Predictive_Modeling_of_Hotel_Cancellations_&_Revenue_Optimization.ipynb
├── Predictive_Modeling_of_Flight_Delays_&_Operational_Risk.ipynb
├── README.md
└── requirements.txt
