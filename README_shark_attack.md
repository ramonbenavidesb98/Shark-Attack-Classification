# Shark Attack Fatality Classification

A machine learning project predicting the likelihood of a fatal outcome in shark attack incidents using historical global data. Demonstrates classification modeling, clustering, class imbalance handling, and statistical validation — skills directly applicable to risk scoring, anomaly detection, and rare event prediction in any industry.

---

## Business Problem

Rare event classification is a core challenge across industries — fraud detection, equipment failure prediction, medical diagnosis. This project tackles that challenge using the Global Shark Attack File: given incident characteristics, can we reliably predict whether an attack will be fatal?

The same modeling approach applies to: predicting customer churn, identifying fraudulent transactions, or flagging high-risk operational events.

---

## Key Results

| Model | Accuracy | Notes |
|---|---|---|
| Logistic Regression | ~72% | Baseline |
| Decision Tree | ~76% | Interpretable |
| Random Forest | ~80% | Strong generalization |
| **XGBoost** | **>80%** | **Best overall performance** |

- **Top predictors:** shark species, victim activity, geographic region
- **3 meaningful risk clusters** identified via KMeans — segmented by age, time of incident, and fatality rate
- **Class imbalance handled** via SMOTE and hybrid resampling — critical for rare event modeling
- **Statistical validation** via ANOVA and Chi-Square tests confirmed key feature significance

---

## Techniques Used

- **Classification:** Logistic Regression, Decision Trees, Random Forest, XGBoost
- **Clustering:** KMeans segmentation
- **Class Imbalance:** SMOTE, undersampling, hybrid approaches
- **Statistical Testing:** ANOVA, Chi-Square
- **Feature Engineering:** Activity type, season, time of day, weekend/weekday flag

---

## Stack

`Python` · `scikit-learn` · `XGBoost` · `imbalanced-learn` · `Pandas` · `Matplotlib` · `Seaborn`

---

## Files

| File | Description |
|---|---|
| `Project Code.ipynb` | Full analysis — EDA, feature engineering, modeling, clustering |
| `attacks.csv` | Global Shark Attack File dataset |
| `Final Written Project Report.pdf` | Full writeup with methodology and findings |

---

## Context

Completed for ISyE 7406: Data Mining & Statistical Learning at Georgia Tech (MS Analytics). Group project — my contributions included leading EDA and feature engineering, developing and evaluating all classification models, and performing the clustering and hypothesis testing.

---

## About

Built by **Ramon Benavides** — analytics professional with nearly 3 years of experience building data pipelines, forecasting models, and decision-support systems.

- [Portfolio](https://ramonbenavidesb98.github.io)
- [LinkedIn](https://linkedin.com/in/ramonbenavides)
- [GitHub](https://github.com/ramonbenavidesb98)
