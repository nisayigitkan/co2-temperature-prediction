# 🌍 Climate Change Analysis: CO₂ Concentration and Global Temperature Prediction

This project explores the historical relationship between atmospheric CO₂ concentrations and global temperature anomalies using various data science techniques. The analysis was performed in **Google Colab** using Python libraries such as `pandas`, `scikit-learn`, `matplotlib`, and `statsmodels`.

---

## 📌 Project Objectives

- Analyze correlation and causality between CO₂ levels and global temperature change.
- Perform statistical tests including:
  - Pearson & Spearman correlation
  - Granger causality test
  - Ordinary Least Squares (OLS) regression
- Apply **unsupervised machine learning (KMeans clustering)** to segment historical climate patterns.
- Run **“What If” simulation scenarios** to predict how hypothetical CO₂ concentration changes might affect global temperatures using linear regression.

---

## 📊 Techniques Used

- 📈 **Correlation Analysis**  
  Understand the linear (Pearson) and rank-based (Spearman) relationships between variables.

- 🔄 **Granger Causality Test**  
  Evaluate if past values of CO₂ help predict temperature change.

- 📉 **Linear Regression Model**  
  Predict temperature changes under simulated CO₂ scenarios.

- 📌 **Lagged Variables**  
  Include past CO₂ values to examine delayed effects on temperature.

- 🎯 **Clustering**  
  Identify distinct climate periods based on CO₂ and temperature levels.

---

## 💡 Key Results

- Strong positive correlation between CO₂ concentration and temperature anomaly (Pearson ≈ 0.91).
- Granger test shows significant causality from CO₂ to temperature at various lags.
- OLS regression yielded an R² ≈ 0.95, indicating a strong predictive model.
- “What-If” scenarios revealed:
  - 🔺 10% CO₂ increase → +1.09°C predicted
  - 🔻 10% CO₂ decrease → -0.06°C predicted
  - 🔺 20% CO₂ increase → +1.66°C predicted
  - 🔻 20% CO₂ decrease → -0.63°C predicted

---

## 📎 Files

- `co2_temperature_analysis.ipynb` → Main Colab notebook
- `data.csv` → Historical CO₂ and temperature data
- `newplot.png`, `cluster_plot.png` → Visualizations

---

## 🔧 Technologies

- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Statsmodels
- Matplotlib, Seaborn

---

## 📬 Author

**Nisa Aktaş**  
Feel free to reach out on [LinkedIn](https://www.linkedin.com/) for collaboration or questions.

---

## 📜 License

This project is open-source and available under the MIT License.
