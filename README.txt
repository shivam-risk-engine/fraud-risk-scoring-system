# Rule-Based Fraud Risk Scoring System (Python)

## 📌 Overview
This project is a simple rule-based fraud risk scoring system built using Python.

It calculates a risk score based on claim amount, number of past claims, and age, and then classifies each case into different risk levels.



## 🧠 How it works

The system uses simple business rules to simulate fraud risk evaluation:

### Fraud Score Rules:
- High claim amount (> 50,000) → +0.4  
- Frequent past claims (> 3) → +0.3  
- Young age (< 25) → +0.2  

### Decision Rules:
- Score ≤ 0.2 → Low Risk (Approve)  
- Score ≤ 0.5 → Medium Risk (Review)  
- Score ≤ 0.8 → High Risk (Investigate)  
- Score > 0.8 → Very High Risk (Strict Investigation)  



## 🚀 What I learned
- How rule-based systems are used in fraud detection  
- How risk scoring is applied in insurance and financial systems  
- Decision-making under uncertainty is more important than just prediction accuracy  



## 🛠 Tech Used
- Python



## 🎯 Purpose
This project is part of my learning journey in:
- Data Analytics  
- Actuarial Thinking  
- Risk-based decision systems  