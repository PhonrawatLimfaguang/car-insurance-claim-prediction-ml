# 🚗 Car Insurance Claim Prediction
> **Predicting high-risk policyholders using Machine Learning & SMOTE**

This project addresses the challenge of predicting car insurance claims in a **highly imbalanced dataset**. We implemented various classification algorithms and ensemble techniques to optimize risk detection.

---

## 📊 Performance Summary
We compared multiple models, focusing on **Recall** for the minority class (Claim = 1), as missing a potential claim is more costly for insurance companies.

| Model | Accuracy | Recall (Class 1) | F1-Score |
| :--- | :---: | :---: | :---: |
| **XGBoost (+SMOTE)** | **0.6575** | **0.3939** | **0.1313** |
| **LightGBM (+SMOTE)** | **0.6623** | **0.5099** | **0.1656** |
| **Random Forest** | 0.5638 | 0.6052 | 0.1542 |



---

## 🛠️ Key Methodologies
1. **Handling Imbalance:** Applied **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the target classes.
2. **Feature Engineering:** One-Hot Encoding for categorical data and Scaling for numeric features.
3. **Advanced Modeling:** Utilized **Ensemble Learning** (XGBoost, LightGBM) and **Deep Learning** (MLP) for robust prediction.
4. **Evaluation:** Shifted focus from Accuracy to **Recall and F1-Score** to better reflect business objectives.

---

## 📁 Project Contents
* `*.ipynb`: Full analysis pipeline (EDA, Preprocessing, Modeling).
* `*.pdf`: Final research report with detailed insights.
* `*.py`: Production-ready Python script.

## 🔗 External Links
* 🎥 **Presentation:** [https://youtu.be/essfIuOh6u8](https://youtu.be/essfIuOh6u8)
* 🖼️ **Slides:** [View on Canva](https://www.canva.com/design/DAG2cMqZHRo/4XP2e45QOYlKbOVnWow2zQ/view)

---
**Course:** DE361 Machine Learning, Srinakharinwirot University (SWU)
