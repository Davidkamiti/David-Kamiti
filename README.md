# Hi, I'm David Kamiti

I'm a junior data scientist who builds machine learning models, tests them honestly, and turns them into tools people can use. I'm open to **junior data science and machine learning roles**.

## Projects

### [Credit Risk Prediction](https://github.com/Davidkamiti/credit-risk-prediction) ([live demo](https://credit-risk-prediction-xsm9tmmnd8gxkixqihejkg.streamlit.app/))
A tuned Random Forest that estimates loan default risk, deployed as a Streamlit app.
- ROC-AUC **0.91**; at a 0.6 threshold, 81% precision and 71% recall on defaulters
- Handled class imbalance with SMOTE, and documented the precision/recall trade-off behind the threshold
- Rebuilt the training pipeline so the scaler and model ship together, and wrote down the evaluation weaknesses I found (threshold chosen on test data, SMOTE before cross-validation)

### [Telecom Customer Churn](https://github.com/Davidkamiti/phase-3-project)
Compared six model types and tuned XGBoost for F1 on the churn class instead of accuracy.
- Catches **95 of 121** churners on held-out data, with 84% precision
- Found that customers with an international plan churn at **42%** (11% without) and that churn jumps to **52%** after 4 or more customer service calls
- Threshold chosen on training data only, with cross-validation and permutation importance

### [What Do Hacker News Hiring Posts Ask For?](https://github.com/Davidkamiti/data-job-skills-nlp)
A text analysis of **3,691 job posts** collected through an API, extracting skills and tracking demand over 12 months.
- Found that SQL appears in only 4% of posts and that LLM mentions stayed flat (about 12% to 15%)
- Checked my own skill matcher against an independent count, and fixed a flawed headline rule after finding it flagged company names

## Skills

**Languages and libraries:** Python, pandas, NumPy, scikit-learn, XGBoost, imbalanced-learn, matplotlib
**Methods:** classification, feature engineering, hyperparameter tuning, cross-validation, threshold selection, text mining
**Tools:** Streamlit, Git and GitHub, Jupyter
**Coursework:** SQL, hypothesis testing, A/B testing, regression, NLP

## How I work

I report the numbers that make a model look worse as well as better, and each project's README lists its limitations.

## Contact

- GitHub: [Davidkamiti](https://github.com/Davidkamiti)
- LinkedIn: [David Kamiti](https://www.linkedin.com/in/david-kamiti-71b109278/)
- Email: davidkamiti479@gmail.com

