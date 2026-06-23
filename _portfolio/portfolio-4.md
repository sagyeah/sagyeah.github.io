---
title: "Distribution Function Estimation for Sensitive Quantitative Variables"
collection: portfolio
author_profile: false
---

This research investigates Monte Carlo-based approaches for estimating the cumulative distribution function (CDF) of sensitive quantitative variables — data that respondents may misreport due to social desirability bias (e.g., income, sensitive health behaviors, or personal finances).

The study compares two indirect questioning methods:
- **Item Sum Technique (IST)** — respondents report the sum of a sensitive item and a non-sensitive distractor, protecting individual privacy while enabling unbiased population-level estimation
- **Item Sum Double List Technique (ISDLT)** — a two-group extension of IST that improves estimation efficiency and reduces variance

Using Monte Carlo simulation in R (500 replications per setting), the project evaluates CDF estimators under varying sample sizes (n = 100, 500), correlation structures (ρ = −0.5, 0, 0.5), and distributional assumptions (Beta-distributed sensitive variable, Uniform distractor). Social desirability bias is explicitly modeled to demonstrate how under-reporting distorts naive direct estimates and how IST/ISDLT correct for this.

**Key contributions:**
- Designed and implemented the full simulation pipeline in R using `ggplot2`, `MASS`, and custom CDF estimators
- Evaluated bias, MSE, and visual fit of IST and ISDLT estimators against direct and kernel-based alternatives
- Extended the framework to quantile estimation and real-data application
- Assisted with manuscript preparation and coding as a Graduate Research Assistant

This project was developed under the supervision of Dr. Abeer Hasan, Department of Mathematics, North Carolina A&T State University, in connection with an NSF-funded research program.

---

🔗 **[View Full Project on GitHub](https://github.com/sagyeah/IST-ISDLT-CDF-Estimation){:target="_blank"}**
