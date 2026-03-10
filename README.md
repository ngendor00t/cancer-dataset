# cancer-dataset
**Tools:** Python, Pandas, Matplotlib 
**Dataset:** 1,000 cancer patient 25columns
Exploratory data analysis projects using Python and pandas

## Project Overview

This project analyzes a cancer patient dataset to identify key risk factors, symptom predictors, and demographic patterns that drive High cancer risk. The goal was to uncover actionable insights that could help healthcare organizations identify at-risk patients earlier.
### Column Categories
- **Patient Info** → Patient ID, Age, Gender
- **Risk Factors** → Smoking, Air Pollution, Alcohol Use, Genetic Risk, Obesity, Dust Allergy, Occupational Hazards, Balanced Diet, Chronic Lung Disease
- **Symptoms** → Chest Pain, Coughing of Blood, Fatigue, Weight Loss, Shortness of Breath, Wheezing, Frequent Cold, Dry Cough, Snoring
- **Outcome** → Level (Low / Medium / High)

## Data Cleaning Steps
loaded the dataset
worked on a copy to not change the original data 
standardized column names 
checked for missing data or duplicated the data was pretty clean

### Issues Found & Fixed
column names inconsitency 
data into digits instead of label like gender 1 or 2 instead of female or male created gender label

## findings
### Q1: Do males and females have different risk profiles?
Males show significantly higher risk profiles than females, particularly in Alcohol Use (Male: 5.05 vs Female: 3.84) and Dust Allergy (Male: 5.50 vs Female: 4.67). This explains why males dominate the High risk category with 252 patients compared to 113 females.
Healthcare organizations should consider targeting alcohol awareness and dust exposure prevention programs specifically towards male patients.

### Q2: Are younger patients getting High risk diagnoses?
Age alone does not determine cancer risk —all three levels share a similar average age of 35–38 years. However, 104 patients under 30 fall in the High risk category, driven primarily by high Genetic Risk (6.46) and Alcohol Use (6.37) scores. This suggests hereditary and lifestyle factors are more dangerous predictors than age alone.

### Q3: Which symptoms best predict cancer level?
coughing blood is the highest symptom in the cancer dataset


### Q4: Which risk factors drive High cancer risk the most?
Alcohol Use scores highest among High risk patients at 6.83, however the narrow gap between the top 5 risk factors suggests cancer risk is not driven by any single factor. Instead it is the combination of Alcohol Use, Balanced Diet, Dust Allergy, Occupational Hazards and Genetic Risk that collectively push patients into the High risk category. Frequent Cold is the weakest risk driver with a notably lower score of 4.38.

---

##  Key Overall Findings
| # | Finding |
|---|---|
| 1 | Males are twice as likely to be High risk, driven by Alcohol Use and Dust Allergy |
| 2 | Age is NOT a strong predictor — young patients under 30 can still be High risk |
| 3 | Coughing of Blood is the single strongest symptom predictor of High cancer risk |
| 4 | Cancer risk is combinational — no single factor drives it alone |
| 5 | Alcohol Use is the most consistent risk factor appearing across all analysis angles |








