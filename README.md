# biopharma-batch-analysis

# Biopharma Batch Process Analysis

This project explores variability and quality outcomes in biopharmaceutical batch manufacturing using real or simulated datasets. It aims to detect bad batches, identify key process drivers, and recommend process improvements using machine learning.

## 📊 Project Goals
- Analyze batch-to-batch variability in yield and process parameters
- Visualize trends and detect outliers using PCA and control charts
- Predict batch outcomes (pass/fail) using classification models
- Interpret model results with SHAP or permutation importance

## 🔧 Tools & Technologies
- Python, Pandas, Scikit-learn, XGBoost
- Seaborn, Matplotlib, SHAP
- Streamlit (for optional dashboard)

## 📁 Key Notebooks
- `01_exploratory_analysis.ipynb`: Correlation plots, PCA, control charts
- `02_modeling.ipynb`: Logistic regression, Random Forest, XGBoost
- `03_feature_importance.ipynb`: SHAP values for interpretation

## 🔍 Dataset Source
- Based on [Nature Scientific Data](https://www.nature.com/articles/s41597-022-01203-x)
- Synthetic data generator may be used for reproducibility

## 🚀 Outcomes
- Feature importance highlights which parameters impact batch success
- Clear identification of abnormal batch runs
- (Optional) Real-time dashboard for monitoring

## 📌 To Do
- [ ] Simulate or clean batch data
- [ ] Complete exploratory analysis
- [ ] Train classifier
- [ ] Deploy dashboard (optional)

