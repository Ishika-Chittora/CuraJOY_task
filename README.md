# CuraJOY_task
# Cyberbullying Detection Solution – curaJOY Impact Fellowship Challenge

This repository branch contains the solution developed as part of the Cyberbullying Detection Recruitment Challenge for curaJOY’s Impact Fellowship Program 2025.

## 📌 Challenge Objective
Build robust cyberbullying detection models using machine learning and NLP to classify online text comments into bullying or non-bullying categories. The project aims to protect adolescents by detecting harmful behavior across online platforms.

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `Model_training.ipynb` | Full pipeline: preprocessing, model training (Logistic, SVC, RF, XGBoost, LSTM, Voting), and evaluation |
| `Preprocessing.ipynb` |Preprocessing code|
| `requirements.txt` | List of all Python dependencies |
| `Cyberbullying Detection Challenge.pdf` | 3-page documentation of the full solution |
|`preprocessed_cyberbulliying_data' | preprocessed or cleaned data |

---

## 🛠️ Models Implemented

- Logistic Regression
- Support Vector Classifier (SVC)
- Random Forest Classifier
- Voting Classifier (Ensemble)
- LSTM (Deep Learning)
- XGBoost Classifier

> ✅ All models are evaluated using accuracy, precision, recall, and F1-score.

---

## 📊 Results Summary

| Model              | Accuracy | Precision | Recall | F1 Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | ~84.4%  | ~38.9%    | ~41.2% | ~40.0%   |
| SVC                 | ~86%    | ~41.6%    | ~29.4% | ~34.4%   |
| Random Forest       | ~88.1%  | ~55.5%    | ~29.4% | ~38.4%   |
| Voting Classifier   | ~87.4%  | ~50.0%    | ~11.7% | ~19.0%   |
| LSTM                | ~87.4%  | ~0.0%     | ~0.0%  | ~0.0%    |
| XGBoost             | ~85.9%  | ~40.0%    | ~23.5% | ~29.6%   |

---

## 🚀 How to Run

1. Clone this branch:
   ```bash
   git clone -b your-branch-name https://github.com/curaJOY/mcj-ml-pipelines.git
