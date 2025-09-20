# Description
This project, conducted in collaboration with **LSE Philanthropy and Global Engagement (LSE PAGE)**, analyzes the drivers of **legacy donation among alumni**. Legacy giving is a growing strategic priority for LSE, providing sustainable long-term funding for scholarships, research, and institutional development. By applying data-driven methods to real alumni records, this work delivers meaningful and actionable insights to support PAGE’s legacy marketing programme. Using a combination of traditional statistical models and advanced machine learning techniques, we study demographic, engagement, and donation-related features to uncover the key factors that influence legacy giving.

# Machine Learning Models
- Gradient-based models: GBDT, XGBoost, LightGBM, CatBoost
- Traditional models: logistic regression with/without L1, Decision Trees, Random Forest 
- Unsupervised learning: Factor Analysis, Cluster Analsis

# Pipeline & Key Visuals
**Pipeline**

**Key Visuals** 
<figure>
  <img src="https://github.com/user-attachments/assets/c2d43eb3-3cd8-4cca-9428-ce59849efb17" width="600"><br>
  <figcaption align="center">1.ROC Curve of Fine-tuned Models Using Random Search</figcaption>
</figure>

<figure>
  <img src="https://github.com/user-attachments/assets/8615ac82-8461-4524-bc24-d0b4206ec197" width="600"><br>
  <figcaption align="center">2.Top 10 XGBoost Feature Importances (Random Search) </figcaption>
</figure>


# Highlights
- **Consistent giving behavior** and **total donation amount** in other categories are the strongest predictors of legacy donation.

- **Engagement** activities such as networking event participation and alumni circle involvement significantly increase the likelihood of legacy pledges.

- **Gradient-boosting models** (GBDT, XGBoost) provided the best predictive performance, confirming and extending insights from logistic regression and traditional tree models.

# Recommendations
- Apply predictive scoring to **identify high-propensity alumni** and focus outreach resources where impact is greatest.

- Use model insights to **design targeted marketing campaigns**, highlighting engagement opportunities most likely to convert interested donors into legacy pledgers.

- Leverage donor journey patterns to **tailor messaging**, ensuring communications align with alumni giving behaviors and engagement profiles.
