# Abalone Predictive Modeling
Statistical Learning · GLM · PCA · Model Diagnostics  

---

## Project Overview

This project investigates the latent morphological structure of abalone measurements and builds statistically principled predictive models for estimating abalone age (measured by shell ring counts).

The dataset contains 4,177 observations of physical measurements including:

- Length  
- Diameter  
- Height  
- Whole weight  
- Shucked weight  
- Viscera weight  
- Shell weight  

The primary objective is to:

1. Explore dimensional structure using Principal Component Analysis (PCA)
2. Conduct inference via permutation testing and bootstrap resampling
3. Construct and compare Negative Binomial GLMs for count prediction
4. Diagnose multicollinearity using Variance Inflation Factors (VIF)
5. Evaluate predictive performance using out-of-sample metrics

---

## Statistical Methods

1. Exploratory Data Analysis
2. Principal Component Analysis
3. Predictive Modeling Framework

## Out-of-Sample Evaluation

Models were evaluated using:

- RMSE
- MAE
- Test Deviance
