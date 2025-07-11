# 🏥 Interpretable Machine Learning in Healthcare

This project explores the use of interpretable machine learning methods to optimize hospital bed allocation during a healthcare crisis, such as the COVID-19 pandemic. It combines data science, ethical decision-making, and operations research to create a robust, transparent support system for medical resource management.

## 🔍 Problem Statement
During health emergencies, hospitals face bed shortages. The goal is to **minimize mortality** by:
- Prioritizing patients fairly
- Allocating limited resources efficiently
- Maintaining model interpretability for clinical transparency

## 🧠 Methodology

- **Data Simulation**: Synthetic population with realistic patient features (age, comorbidities, risk score)
- **Optimization**: Linear programming (`scipy.optimize`) to allocate beds based on a cost minimization function
- **Prediction**: Random Forest model trained to replicate the optimization outputs
- **Dimensionality Reduction**: PCA used to improve generalization and interpretability
- **Explainability**: Feature importance analysis to highlight clinical reasoning

## 📦 Tech Stack
- Python
- Scikit-learn
- Pandas / NumPy
- Scipy
- Matplotlib / Seaborn

## 📊 Results
- Achieved high alignment between optimization and model prediction
- Feature importance highlighted patient severity and triage score as primary drivers
- The model mimics decision-making of an ideal planner, allowing fast inference in emergencies

## ✨ Why This Matters
In high-stakes environments, **black-box models can’t be trusted**. This project shows how interpretable AI can empower healthcare workers with:
- Transparency
- Trust
- Speed
