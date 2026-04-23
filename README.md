# federated-learning-fraud-detection
# Robust Federated Learning for Fraud Detection

## 📌 Overview
This project implements a secure Federated Learning system for credit card fraud detection, designed to resist adversarial attacks.

## 🚨 Problem
Federated Learning is vulnerable to poisoning attacks where malicious clients send corrupted updates.

## ✅ Solution
We propose a multi-layer defense:
- VAE-based anomaly detection
- Trimmed Mean aggregation
- Rollback mechanism

## ⚙️ Features
- Non-IID client simulation (Dirichlet distribution)
- SMOTE for class imbalance
- Malicious + stealth attack simulation
- PCA and histogram visualization

## 📊 Results
| Model | ASR |
|------|------|
| FedAvg | 1.0 |
| Trimmed Mean | 1.0 |
| VAE | 0.5–1.0 |
| Full Model | **0.0–0.5** |

## 📁 Project Structure
See folder organization above.

## ▶️ Run the Project

```bash
pip install -r requirements.txt
python main.py
