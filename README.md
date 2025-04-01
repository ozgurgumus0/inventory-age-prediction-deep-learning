# 📦 Inventory Age Prediction using Deep Learning in Alcoholic Beverage Industry

This project is an undergraduate thesis for Yıldız Technical University Industrial Engineering Department focused on **predicting inventory age** in warehouses for an alcoholic beverage company using **machine learning** and **deep learning** algorithms. The goal is to help optimize inventory management by predicting how long products will stay in storage — a key cost factor in fast-moving consumer goods (FMCG).

---

## 🎯 Problem Definition

The company operates 3 warehouses and manages 62 products across 19 product groups. Predicting inventory age helps reduce storage costs, avoid spoilage, and optimize logistics. We used real-life inventory data and built models to forecast product aging behavior.

---

## 🧠 Models Used

### ✅ Machine Learning
- Linear Regression  
- Polynomial Regression with Ridge  
- Support Vector Machine (SVM)  

### ✅ Deep Learning
- Multilayer Perceptron (MLP)  
- Recurrent Neural Networks (RNN)  
- Long Short-Term Memory (LSTM)  
- **Echo State Networks (ESN)** ← 🏆 Best performance

---

## 📊 Results

| Model                 | R² Score |
|----------------------|----------|
| Linear Regression     | 0.23     |
| Polynomial w/ Ridge   | 0.59     |
| SVM                   | 0.11     |
| MLP                   | 0.64     |
| RNN                   | 0.68     |
| LSTM                  | 0.72     |
| **ESN**               | **0.85** |

---

## 📁 Files

- `code/` – Final implementation in Python (Jupyter Notebook)
- `report/` – Full thesis in DOC format
- `presentation/` – Defense presentation slides
- `poster/` – Project summary poster

---

## 🧰 Technologies Used

- Python (Pandas, Sklearn, TensorFlow/Keras)
- Jupyter Notebook
- Excel (data analysis phase)
- Word / PowerPoint for documentation

---

## 🧾 Citation

**Özgür Gümüş & Melis Kamacıoğlu**  
BSc Thesis – Industrial Engineering  
Marmara University, 2023  
Advisor: Prof. Dr. Alev Taşkın

---

> This thesis proposes ESN as a highly effective model for inventory age forecasting and highlights its potential for future research and practical supply chain optimization in the FMCG sector.
