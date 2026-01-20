# Trends-Analyzing-and-Risk-detection-System
UIDAI Intelligence Platform is a Streamlit-based dashboard that unifies Aadhaar Enrolment, Demographic, and Biometric datasets. It shows trends, state comparisons, age insights, and a Risk Intelligence layer that tags states as Low, Medium, or High risk for smart governance.
# UIDAI Intelligence Platform

A data-driven government dashboard built using Streamlit to analyze Aadhaar Enrolment, Demographic Updates, and Biometric Updates across India.

This project unifies three real UIDAI datasets into a single interactive platform and provides:
- State-wise and monthly trends  
- Age-group analysis (0–5, 5–17, 18+)  
- Top & bottom performing regions  
- Mini state comparison charts  
- A Risk Intelligence Layer with an Identity Risk Index (IRI)

The Risk Layer computes IRI using:
- Enrolment gaps vs expected population  
- Enrolment velocity  
- Biometric churn  
- Demographic volatility  

Each state is tagged as **Low / Medium / High Risk** with clear reasons and suggested actions.

## Tech Stack
- Python  
- Streamlit  
- Pandas  
- Matplotlib  

## How to Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py
