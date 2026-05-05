
# 🌍 Country Clustering using Unsupervised Learning

This project applies unsupervised machine learning techniques to cluster countries based on socio-economic and health indicators. The goal is to identify patterns in global development and highlight countries that may require financial aid.

The dataset used in this project is from Kaggle:
https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data

---

## 📌 Problem Statement

This project is inspired by a real-world scenario involving an NGO called **HELP International**.

The organization has raised funds and needs to decide how to allocate resources effectively. The objective is to:

- Categorize countries based on development indicators  
- Identify the countries most in need of economic support  

This is achieved using clustering techniques. :contentReference[oaicite:0]{index=0}

---

## 📊 Dataset Description

The dataset contains **167 countries** and **10 features**, including:

- `child_mort` – Child mortality rate  
- `income` – Net income per person  
- `gdpp` – GDP per capita  
- `health` – Health expenditure  
- `imports` / `exports` – Trade indicators  
- `inflation` – Economic growth indicator  
- `life_expec` – Life expectancy  
- `total_fer` – Fertility rate  

These features represent both **economic** and **health conditions**, which are key indicators of a country's development. :contentReference[oaicite:1]{index=1}

---

## 🧠 Techniques Used

- Data Cleaning & Exploration  
- Feature Selection  
- Data Normalization (Scaling)  
- PCA (Principal Component Analysis)  
- Clustering Algorithms:
  - K-Means  
  - DBSCAN  

---

## ⚙️ Project Workflow

1. Data preprocessing  
2. Feature selection  
3. Data normalization  
4. Dimensionality reduction (PCA)  
5. Model training:
   - K-Means clustering  
   - DBSCAN clustering  
6. Evaluation:
   - Silhouette Score  
   - Calinski-Harabasz Score  

---

## 📈 Results & Insights

- Countries were successfully grouped into clusters based on similarity  
- One cluster represents **underdeveloped countries**, characterized by:
  - High child mortality  
  - Low GDP per capita  
  - Low income  

These countries are the most likely candidates for financial aid.

---

## 🛠️ Tools & Libraries

- Python 🐍  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 🚀 Future Improvements

- Apply Hierarchical Clustering  
- Improve feature engineering  
- Add interactive visualizations (Plotly)  
- Deploy as a web app  

---

## 📌 Author

**Ibtissame Achlauchi**  
Student in Computer Science & Artificial Intelligence  

---
