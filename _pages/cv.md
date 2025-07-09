---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. Applied Mathematics (Statistics and Data Science)
   North Carolina A&T State University, Greensboro, NC 
   GPA: 3.9/4.0 – *Expected 2026*

* BSc. Mathematics
    Kwame Nkrumah University of Science and Technology, Kumasi, Ghana  
    GPA: 3.3/4.0 – *2022*

Work experience
======
* **Graduate Teaching Assistant**, North Carolina A&T State University  
  *Aug 2024 – Present*  
  - Taught undergraduate statistics (STAT 224) using R.  
  - Helped students build statistical intuition and code reproducible reports.  
  - Conducted weekend help sessions and one-on-one tutoring
* Supervisor: Dr. Sayed Mostafa

* **Data Analyst**, Ghana Commercial Bank PLC – Accra, Ghana  
  *Sep 2022 – Jul 2024*  
  - Increased processing efficiency by 15% using R and SQL.  
  - Performed sentiment analysis, helping reduce account closures by 21%.  
  - Streamlined data pipelines, reducing redundancy by 25%.

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
- **Programming:** R, Python, SQL 
- **Data Visualization:** Power BI, Tableau, ggplot2  
- **Statistical Techniques:** Regression, Machine Learning, Simulation  
- **Tools:** Git, LaTeX, Excel, Jupyter, R Markdown 



Selected Projects
======

*1. Body Fat Analysis & Prediction (Certification Project)*  
*April 2025*  
Used linear, ridge, and lasso regression to model body fat percentage from anthropometric data (436 individuals).  
- Applied cross-validation and performance metrics (MSE, R²).  
- Lasso regression achieved the best predictive accuracy with interpretable variable selection.  
- Tools: `dplyr`, `glmnet`, `ggplot2`

*2. Bootstrap vs Jackknife Variance Estimation (Simulation Study)*  
*STAT 711 Project, Spring 2025*  
Monte Carlo study comparing bias and MSE of bootstrap and jackknife estimators for Pearson’s correlation under bivariate normal and lognormal distributions.  
- 10,000 simulations for each setting.  
- Bootstrap showed superior performance especially under skewed (lognormal) data.  

*3. Heart Attack Risk Prediction Using ML*  
- Modeled heart attack risk using demographic + lifestyle data.  
- Algorithms: Logistic Regression, Decision Trees, Random Forest.  
- Evaluated using sensitivity, specificity, precision, and accuracy

*4. Fuzzy Logic in Transportation Cost Optimization*  
- Compared Vogel’s, Least Cost, and Northwest Corner methods.  
- Applied fuzzy logic to cost/supply/demand to generate more realistic solutions.

  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Organized weekly student study groups for statistics help sessions.  
* Participated in departmental curriculum feedback meetings (2024–2025).  
* Previously served as club treasurer (BONABOTO KNUST), optimized budgets.
