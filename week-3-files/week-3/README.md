# Week 3 — Python-Based Machine Learning Model Development and Evaluation Plan

## Objective
Design a detailed, step-by-step plan for developing and evaluating a machine learning model in Python — covering problem definition, preprocessing, model selection, training, evaluation, and deployment considerations.

## Deliverable
📄 [`Week3_ML_Model_Development_Plan.docx`](./Week3_ML_Model_Development_Plan.docx)

## Project Framing
Extends the [[climate-risk-dashboard]] project from Week 1 into a supervised classification problem: predicting a facility's climate risk category (Low / Medium / High) from climate, air-quality, and operational features.

## What's Inside
1. Problem Definition (with justification)
2. Data Preprocessing (cleaning, normalization, feature engineering, challenges table)
3. Model Selection & Training (model comparison table, chosen approach, training process, hyperparameter tuning)
4. Evaluation Metrics & Validation Strategy (confusion matrix, metrics, cross-validation)
5. Model Deployment & Maintenance (optional, conceptual)
6. Conclusion

## Diagrams
| Diagram | Description |
|---|---|
| `ml_workflow.png` | 7-step end-to-end ML workflow, problem definition to deployment |
| `cv_split_diagram.png` | Train/validation/test split + 5-fold cross-validation illustration |
| `eval_metrics.png` | Confusion matrix and derived evaluation metric formulas |

## Candidate Models Compared
Logistic Regression · Decision Tree · Random Forest (chosen) · Gradient Boosting (XGBoost) · SVM

## Tools Identified
`scikit-learn` · `pandas` · `NumPy` · `XGBoost` · `joblib` · `FastAPI` (deployment concept) · `MLflow` (versioning concept)
