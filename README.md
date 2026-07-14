# Bioenhancement-Strategy-Classifier
XGBoost + SHAP classifier predicting oral drug bioenhancement strategies from physicochemical descriptors, trained on AqSolDB (9,982 compounds)
# BioEnhance Agent

Machine learning framework for predicting aqueous drug solubility using molecular descriptors. The project combines automated preprocessing, hyperparameter optimization, ensemble machine learning, and SHAP explainability to support early-stage drug discovery and pharmaceutical formulation research.

---

# 🚀 AI-Based Drug Solubility Prediction with Explainable Machine Learning

BioEnhance Agent provides an end-to-end machine learning pipeline for predicting aqueous solubility of drug-like compounds. The workflow includes data preprocessing, feature engineering, model optimization, explainable AI, and automated visualization to build accurate and interpretable predictive models.

The project is designed for researchers working in computational pharmacy, drug discovery, pharmaceutical sciences, and machine learning.

---

# 📌 Key Features

- Binary classification of aqueous drug solubility
- Automated preprocessing pipeline
- Feature selection and scaling
- Hyperparameter optimization using Optuna
- Multiple machine learning algorithms:
  - XGBoost
  - LightGBM
  - CatBoost
  - Random Forest
  - Extra Trees
- SHAP-based model explainability
- Automated evaluation metrics
- Publication-quality figures
- Automatic export of trained models and results

---

# 🧠 Why Drug Solubility?

Poor aqueous solubility remains one of the leading causes of drug development failure, limiting oral bioavailability and therapeutic efficacy.

Accurate prediction of solubility can assist researchers in:

- Early compound prioritization
- Lead optimization
- Formulation strategy selection
- Reducing experimental cost and time
- Supporting data-driven pharmaceutical development

---

# 📊 Dataset

**Source:** AqSolDB – A Curated Aqueous Solubility Dataset

- Thousands of experimentally measured compounds
- Molecular descriptors generated from chemical structures
- Diverse chemical space suitable for machine learning applications

Download the dataset from:

https://www.kaggle.com/datasets/sorkun/aqsoldb-a-curated-aqueous-solubility-dataset

Reference:

Sorkun MC, Khetan A, Er S. *Scientific Data.* 2019.

---

# 🧪 Machine Learning Pipeline

The workflow includes:

- Data cleaning
- Missing-value handling
- Feature preprocessing
- Model training
- Hyperparameter optimization
- Cross-validation
- Model evaluation
- SHAP explainability
- Automatic generation of performance figures

---

# 📈 Outputs

The notebook automatically generates:

- ROC Curve
- Precision–Recall Curve
- Confusion Matrix
- Feature Importance Plot
- SHAP Summary Plot
- Performance Metrics
- Saved Trained Models

---

# ▶️ Running the Notebook

Install dependencies

```bash
pip install xgboost lightgbm catboost optuna shap scikit-learn matplotlib seaborn pandas numpy
```

Download the AqSolDB dataset from Kaggle.

Open `BioEnhance_Agent.ipynb` in Google Colab or Jupyter Notebook.

Run the notebook from top to bottom and upload the dataset when prompted.

The pipeline automatically trains the models, evaluates performance, generates explainability plots, and exports all results.

---

# 🔬 Future Work

Future development will integrate this machine learning framework with large language models (LLMs) to build an interactive pharmaceutical decision-support system. The goal is to combine predictive modeling, explainable AI, and natural-language reasoning to assist formulation scientists during early-stage drug development.

Planned extensions include:

- Molecular structure visualization
- ADMET prediction
- Multi-task learning
- Web-based deployment
- Interactive formulation recommendations

---

# 📚 References

1. Sorkun MC, Khetan A, Er S. AqSolDB. *Scientific Data.* 2019.
2. Chen T, Guestrin C. XGBoost. *KDD.* 2016.
3. Akiba T, et al. Optuna. *KDD.* 2019.
4. Lundberg SM, Lee SI. SHAP. *NeurIPS.* 2017.
5. Williams HD, et al. Strategies to Address Low Drug Solubility in Discovery and Development. *Pharmacological Reviews.* 2013.
6. Amidon GL, et al. A Theoretical Basis for a Biopharmaceutic Drug Classification. *Pharmaceutical Research.* 1995.

---

# 📄 License

MIT License

---

# 👩‍💻 Author

**Mahsa Lotfi, PharmD*

Computational Pharmacy • Machine Learning • Drug Discovery • Explainable AI

GitHub: https://github.com/lotfimahsa24
