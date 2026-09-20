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
* Ph.D. Data Science and Analytics *(Starting Fall 2026)*  
   North Carolina A&T State University, Greensboro, NC

* M.S. Applied Mathematics (Statistics and Data Science)  
   North Carolina A&T State University, Greensboro, NC  
   GPA: 3.93/4.0 – *2026*

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

* **Graduate Research Assistant**, North Carolina A&T State University  
  *Aug 2024 – May 2026*  
  - Contributed to an NSF-funded research initiative on AI integration in data science and statistics education, supervised by Dr. Abeer Hasan, Department of Mathematics.  
  - Designed and ran simulation experiments in R, conducted literature reviews, and helped implement research findings in classroom settings.  
  - Assisted with manuscript preparation and coding for a study on distribution function estimation for sensitive quantitative variables.
  
Skills
======
- **Programming:** R, Python, SQL 
- **Data Visualization:** Power BI, Tableau, ggplot2  
- **Statistical Techniques:** Regression, Machine Learning, Simulation  
- **Tools:** Git, LaTeX, Excel, Jupyter, R Markdown 



Presentations
======

*NISS New Researchers Network Virtual Conference* — June 2025  
"Distribution Function Estimation for Sensitive Quantitative Variables"  
National Institute of Statistical Sciences (NISS) · Virtual  

Selected Projects
======

*1. Distribution Function Estimation for Sensitive Quantitative Variables (Graduate Research)*  
*2024 – 2026*  
Monte Carlo simulation study comparing IST and ISDLT estimators for CDF estimation of sensitive variables under varying sample sizes, correlation structures, and distributional assumptions. Implemented in R with 500 replications per setting. Includes quantile estimation and real-data applications.  
- Supervisor: Dr. Abeer Hasan · NSF-funded · [GitHub](https://github.com/sagyeah/IST-ISDLT-CDF-Estimation)

*2. Body Fat Analysis & Prediction (Certification Project)*  
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
