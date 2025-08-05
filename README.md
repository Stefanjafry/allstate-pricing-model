Allstate Insurance Pricing Model

This project is a step-by-step, interpretable modeling pipeline that predicts auto insurance premiums using real-world customer and policy data from an Allstate insurance survey Built entirely in a Jupyter notebook.

What’s Inside:


• A full linear regression modeling walkthrough  
• Feature engineering with interaction terms and non-linearities  
• Box-Cox transformation to stabilize variance  
• SHAP-style interpretation plots for actionable business insights  
• Clean code, clean output, and clear explanations  

Model Highlights:

- Predicts premium costs using coverage levels, car value, driver age, and regional information
- Handles multicollinearity with VIF filtering and statistical testing
- Adds human-readable model explanations via SHAP-style feature attributions
- Extracts business logic: young drivers + high coverage = high risk; homeowners = safer bets

Why You Should Check It Out:

If you're learning data science, working in actuarial science, or just want to see what a well-communicated ML model looks like.

It’s clean. It’s interpretable. It’s backed by statistical reasoning and designed for real-world insurance applications.

Files Included:

- AllState_Insurance_Model.ipynb — Full modeling walkthrough  
- requirements.txt — All required packages  
- allstate_cleaned.csv — Cleaned input data  

Get Started:
1. Clone the repo:  
   https://github.com/Stefanjafry/allstate-pricing-model

2. Install requirements:  
   `pip install -r requirements.txt`

3. Launch notebook:  
   `jupyter notebook AllState_Insurance_Model.ipynb`

License:

This project is licensed under the MIT License. You are free to use, modify, and distribute the code.
