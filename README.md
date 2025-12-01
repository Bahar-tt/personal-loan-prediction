# Personal Loan Prediction — Logistic Regression & Decision Tree Models

This project is based on a Kaggle dataset for predicting **Personal Loan acceptance** among bank customers.  
The goal is to build, evaluate, and compare **Logistic Regression** and **Decision Tree** models to identify which customers are most likely to accept a personal loan offer.

---

## 🚀 Project Overview

- **Language & Tools:** Python, JupyterLab, pandas, scikit-learn, matplotlib, seaborn  
- **Goal:** Predict whether a customer will accept a personal loan  
- **Models Used:**
  - Logistic Regression (with custom threshold tuning)
  - Decision Tree (with post-pruning)

---

## 📊 Key Results

| Model | Precision | Recall | F1 Score | Accuracy |
|--------|------------|---------|-----------|-----------|
| Logistic Regression (0.37 Threshold) | 0.77 | 0.71 | 0.74 | 0.93 |
| Decision Tree (Post-Pruned) | 0.93 | 0.90 | 0.91 | 0.98 |

✅ **The Decision Tree model (after pruning)** showed the best performance and interpretability.

---

## 🧠 Insights for Business

- Customers aged **35–40**, with **family ≥ 1**, **undergraduate or higher education**, and **mortgage > $100K** are the best loan targets.  
- Customers with **CD accounts** and **high credit card averages** are good prospects but should be monitored for credit risk.  
- **Senior employees** and **digital-only banking users** are less likely to accept loans.

---

## ⚙️ How to Run the Project

1. Clone this repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/personal-loan-prediction.git
   cd personal-loan-prediction
   ```

2. Create a virtual environment and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open JupyterLab:
   ```bash
   jupyter lab
   ```

4. Run the notebooks in `/notebooks` in order:
   - `logistic_regression_model.ipynb`
   - `decision_tree_model.ipynb`

---

## 🧩 Dependencies

```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---
##images
![Confusion Matrix](images/confusion_matrix.jpg)

![Correlation Heatmap](images/corralationHeatMap.jpg)

![Decision Tree](images/DecisionTree.jpg)

![Pair Plot](images/PairPlot.jpg)

![Loan Distribution](images/personalloan2.jpg)


## 👩‍💻 Author

**Razieh Nasehi — Agentic AI Learner**  
Focus: Applied Machine Learning for real-world decision making  
📬 Contact: [r.nasehi88@gmail.com]
