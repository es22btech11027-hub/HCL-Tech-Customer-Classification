# HCL-Tech-Customer-Classification

# Workflow
Ask Customer ID -> Classify with ML model -> Give Classification to LLM(Gemini) -> Generate message accordingly.

# ML-Model: XGBoost
We used XGBoost as it excels on structured tabular data with complex, nonlinear relationships, so is well-suited for our telecom customer classification task.
The model handles diverse numerical and categorical inputs effectively, learns interactions between variables such as overdue amounts, payment delays, and ARPU, and is robust to noise and missing values commonly found in telecom datasets.
