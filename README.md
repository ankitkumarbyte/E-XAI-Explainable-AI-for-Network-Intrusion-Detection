🔐 E-XAI: Explainable AI for Network Intrusion Detection

An explainable, high-performance intrusion detection framework evaluating black-box machine learning models using SHAP and LIME.
📄 Based on a peer-reviewed research paper published at an international conference 

ICDSA_2025_PID_1804_EXAI

📌 Overview

Traditional AI-based Intrusion Detection Systems (IDS) often operate as black boxes, making it difficult for security analysts to understand why a prediction was made. This project introduces E-XAI, a comprehensive framework that:

Evaluates multiple black-box ML and ensemble models

Applies Explainable AI (XAI) techniques (SHAP, LIME)

Provides transparent, human-interpretable explanations

Achieves state-of-the-art accuracy across benchmark IDS datasets

This repository is the official implementation of the research paper:

“E-XAI: Evaluating Black-Box Explainable AI Frameworks for Network Intrusion Detection”
Published at ICDSA 2025 

ICDSA_2025_PID_1804_EXAI

🧠 Key Contributions

✅ Comparative evaluation of black-box ML models for IDS

✅ Integration of Explainable AI (XAI) to improve trust and transparency

✅ Multi-dataset validation for robustness and generalization

✅ High-performance ensemble Voting Classifier (Boosted DT + Bagging RF)

✅ Real-world relevance for Security Operations Centers (SOC)

📊 Datasets Used

The framework is evaluated on three widely used intrusion detection benchmarks:

Dataset	Description
CIC-IDS 2017	Modern network traffic with diverse attack scenarios
NSL-KDD	Improved version of KDD’99 with reduced redundancy
SIMARGL 2021	High-quality bidirectional flow-based intrusion data
⚙️ Models Implemented

Deep Neural Networks (DNN)

Multi-Layer Perceptron (MLP)

Random Forest

LightGBM

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

AdaBoost

🔥 Voting Classifier (Boosted Decision Trees + Bagging Random Forest)

🧪 Explainability Techniques

To interpret black-box predictions, the following XAI methods are applied:

SHAP (SHapley Additive Explanations)
→ Global & local feature importance

LIME (Local Interpretable Model-Agnostic Explanations)
→ Instance-level explanations for analyst decision support

These explanations help security analysts understand:

Which features influenced a prediction

Why a network flow was classified as malicious or benign

📈 Results Summary

The ensemble Voting Classifier consistently outperformed other models:

Dataset	Accuracy	Precision	Recall	F1-Score
CIC-IDS 2017	97.9%	98.1%	97.9%	98.0%
NSL-KDD	99.4%	99.4%	99.4%	99.4%
SIMARGL 2021	100%	100%	100%	100%

📌 Results confirm excellent generalization, robustness, and real-world applicability 

ICDSA_2025_PID_1804_EXAI

🖥️ System Pipeline

Data Collection

Data Preprocessing & Feature Engineering

Model Training & Validation (80:20 split)

Ensemble Learning

Explainability Analysis (SHAP / LIME)

Performance Evaluation (Accuracy, Precision, Recall, F1, ROC-AUC)

🧾 Publication

If you use this work, please cite:

Ankit Kumar et al.,
"E-XAI: Evaluating Black-Box Explainable AI Frameworks for Network Intrusion Detection",
Proceedings of ICDSA 2025.


📄 Paper included in this repository 

ICDSA_2025_PID_1804_EXAI

👨‍💻 Author

Ankit Kumar
M.S. Artificial Intelligence, Brandenburg University of Technology
AI Researcher | Explainable AI | Network Security

🔗 LinkedIn: https://www.linkedin.com/in/ankit-kumar

⭐ Why This Matters

This project bridges the gap between high-accuracy AI models and human trust, making it suitable for deployment in real-world cybersecurity environments.

If you find this project useful, consider ⭐ starring the repo!
