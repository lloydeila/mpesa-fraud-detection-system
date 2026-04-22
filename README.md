# Mpesa Fraud Detection System

## 🔍 Overview
This project is a mobile-based fraud detection system built using **MIT App Inventor**. It simulates fraud detection in mobile money transactions using a **hybrid approach combining rule-based detection and a Naive Bayes probabilistic model (conceptual/extended).**

The system also uses **TinyDB for local data storage** to record and analyze transaction history.

---

## 🚨 Problem Statement
Mobile money platforms are vulnerable to fraudulent activity such as:
- Suspicious transaction behavior  
- Repeated unauthorized transfers  
- Social engineering-based fraud patterns  

This system demonstrates how fraud can be detected using a combination of **keyword-based rules and probability-based classification concepts**.

---

## ⚙️ Features

### 🔹 Rule-Based Detection (Keyword Pattern Matching)
The system uses predefined **fraud-related and genuine keywords** to evaluate transactions.

- Fraud indicators include suspicious or high-risk keywords  
- Genuine keywords indicate normal or trusted behavior  
- Transactions are analyzed based on the presence of these words  

If fraud-related keywords are detected, the system flags the transaction as **potentially suspicious**.

---

### 🔹 Naive Bayes Probabilistic Model (Conceptual Layer)
The system is extended with a **Naive Bayes machine learning concept** to estimate fraud probability based on transaction patterns.

This model evaluates the likelihood of fraud using:
- Transaction behavior patterns  
- Frequency of activity  
- Keyword occurrence probability  
- Historical classification trends  

:contentReference[oaicite:0]{index=0}

### Purpose:
- Assign probability scores to transactions  
- Improve decision-making beyond simple keyword rules  
- Demonstrate machine learning enhancement potential  

---

### 🔹 Data Storage (TinyDB)
- Stores transaction records locally on the device  
- Maintains history for comparison and analysis  
- Supports rule-based and conceptual ML evaluation  

---

## 🛠️ Tools Used
- MIT App Inventor (application development)  
- TinyDB (local database storage)  
- Android APK Builder  
- Rule-based logic system (keyword detection)  
- Naive Bayes model (conceptual extension)

---

## 🧪 How It Works
1. User enters transaction details  
2. System checks for **fraud and genuine keywords**  
3. Rule-based engine flags suspicious patterns  
4. Naive Bayes model conceptually estimates fraud probability  
5. System outputs:
   - Normal Transaction  
   - Suspicious Transaction 🚨  

---

## 🚀 Future Improvements
- Full Python implementation of Naive Bayes model  
- Natural Language Processing (NLP) for smarter keyword detection  
- Cloud-based transaction database  
- Real-time fraud monitoring system  
- Alert notifications (SMS/email)

---

## 👨‍💻 Author
Lloyd Eila  
Aspiring Cybersecurity Analyst | IT & Security Enthusiast
