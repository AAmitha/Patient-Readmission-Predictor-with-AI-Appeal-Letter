# 🚑 Patient Readmission Predictor with AI Appeal Letter ✉️

A powerful healthcare ML project that predicts patient readmissions and auto-generates insurance appeal letters using **Gemini LLM**, **SHAP Explainability**, and **PDF Export**.

![Python](https://img.shields.io/badge/Python-3.10-blue.svg) ![ML](https://img.shields.io/badge/Model-RandomForest-success) ![AI](https://img.shields.io/badge/LLM-Gemini-lightblue) ![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 🔍 Overview

This project solves a real-world healthcare problem: reducing readmission rates and easing insurance appeals. It includes:

- ✅ **ML Model**: Predict if a patient will be readmitted in <30 days
- 📊 **Explainability**: SHAP values identify top risk factors per patient
- 🧠 **Generative AI**: Gemini LLM writes appeal letters for coverage
- 📝 **PDF Export**: Letters are saved and ready for submission

---

## 📁 Project Structure

```bash
.
├── diabetic_data.csv                # Dataset
├── model/                           # Saved RandomForest model
├── outputs/
│   ├── letters/                     # Appeal letter PDFs
│   └── plots/                       # SHAP feature importance
├── Patient_Readmission_Gpt.ipynb    # Complete executable notebook
├── requirements.txt
└── README.md
