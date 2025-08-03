# 🛡 Network Intrusion Detection System (NIDS)

An AI-powered tool for classifying network activity using IBM Watsonx.ai and AutoAI—built entirely without code.

---

## 📌 Project Overview

This system leverages the NSL-KDD dataset and IBM Cloud to detect cyber threats in network traffic. By automating model training and deployment via AutoAI, it enables real-time classification of connections as either normal or anomalous.

---

## 🔧 Technology Stack

- *Platform*: IBM Cloud + Watsonx.ai  
- *Model Builder*: AutoAI (No-Code)  
- *Deployment*: IBM Watson Machine Learning REST API

---

## 🧱 How It Works

### 🟩 Step 1: Project Setup  
- Initialized Watsonx.ai project  
- Connected IBM Cloud Object Storage  

### 🟨 Step 2: Data Upload  
- Used Train_data.csv from NSL-KDD dataset  
- Features: Duration, Protocol Type, Service, etc.  
- Labels: Normal or Specific Attack Types

### 🟦 Step 3: AutoAI Training  
- AutoAI explored multiple model pipelines  
- Automated:
  - Data Preprocessing  
  - Feature Engineering  
  - Algorithm Selection  
  - Hyperparameter Tuning

### 🟪 Step 4: Model Deployment  
- Selected “Snap Decision Tree Classifier”  
- Achieved *99.5% Accuracy*  
- Deployed as REST API via Watson Machine Learning




