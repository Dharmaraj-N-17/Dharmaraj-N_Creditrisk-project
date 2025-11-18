Interpretable Credit Risk Modeling using SHAP and LIME
This project develops and interprets a machine learning model to predict loan default risk based on borrower and loan characteristics. Using gradient boosting (LightGBM), the binary classification model classifies loan applicants as likely to fully pay their loan or default.
Features
•	Uses a comprehensive dataset of loan applications with features like loan grade, applicant income, loan amount, credit history, and more.
•	Handles class imbalance and optimizes model performance using robust evaluation metrics including AUC, precision, recall, and F1-score.
•	Applies SHAP (SHapley Additive exPlanations) and LIME (Local Interpretable Model-agnostic Explanations) for both global and local model interpretability.
•	Compares SHAP and LIME explanations critically in terms of stability, fidelity, and interpretability.
•	Provides local explanations for specific high-risk and low-risk loan applicants, aiding transparency in decision-making.
•	Proposes bias mitigation strategies through regular audits of model explanations to ensure fairness and regulatory compliance.
Deliverables
•	Complete, clean source code for model training, evaluation, and interpretation.
•	Detailed reports on model performance and interpretability.
•	Non-technical summaries designed for business stakeholders.
•	Visualizations including SHAP summary plots, force plots, LIME explanation tables, and evaluation metrics.
Usage
Clone this repository to reproduce the training and explanations. Requirements include Python 3.x, LightGBM, SHAP, LIME, and scikit-learn.
Goals
This project aims to bridge the gap between predictive accuracy and interpretability in credit risk modeling, enabling trustworthy, data-driven lending decisions.
