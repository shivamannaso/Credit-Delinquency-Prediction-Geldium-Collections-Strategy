📊 Credit Delinquency Prediction – Geldium Collections Strategy
This project outlines an AI-powered, explainable decision system to predict customer delinquency and proactively manage credit risk. The solution combines data insights, decision logic, and automated outreach workflows to support Geldium’s collections and customer care strategy.
Project Goals
- Predict which customers are at risk of delinquency
- Enable early and effective outreach through automated workflows
- Improve repayment rates and reduce collection costs
- Promote fair, data-driven financial support decisions
Model Overview
We use a pruned decision tree for its balance of interpretability and predictive power. Top predictors include missed payments, high credit utilization, debt-to-income ratio, low credit scores, and income levels. The model outputs a risk probability and a binary flag for intervention.

✔Modeling Pipeline
- Load and clean data (imputation, outlier handling, encoding)
- Engineer risk-related features (e.g., high utilization and high DTI flags)
- Train and tune decision tree with cross-validation
- Output customer-level risk scores and predicted flags

✔Collections Decision System
- Inputs: Customer demographics, credit metrics, payment history, and account details
- Decision Logic: Combination of model predictions and business rules
- Actions: Tiered outreach from reminders to hardship plans or human review
- Learning: Tracks intervention outcomes for continuous model refinement
- 
✔Safeguards and Ethical AI
We implement fairness checks across customer segments, explainable decision paths, and clear communication with users. The system complies with privacy regulations and includes manual review for high-risk or disputed cases.
Impact Highlights
- 20% reduction in new delinquencies
- 15% increase in on-time repayments
- 25% savings in collection costs
- Improved customer trust and ethical transparency
- Scalable, automated support paired with human oversight
  Refer to above files


