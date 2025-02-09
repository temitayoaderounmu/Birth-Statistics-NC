# Statistical Analysis of Maternal Health Data in North Carolina

## Overview

Welcome to the maternal health data analysis project! 🎉 In this project, we’re diving into the statistics of maternal health data from North Carolina, looking at key aspects such as maternal age, gestation periods, baby birth weights, and more! 📊 We’ve used a variety of statistical methods (including t-tests, z-tests, and chi-square tests) to uncover some insightful conclusions based on data from 1,409 records. 

## What’s Inside?

### 1. **Mean Age of Mothers Giving Birth** 👩‍👧
**Hypothesis:**
- **Null Hypothesis (H0):** μ ≤ 25 (The mean age of mothers is less than or equal to 25)
- **Alternative Hypothesis (Ha):** μ > 25 (The mean age of mothers is greater than 25)

**Test Results:**
- t-statistic = 11.052
- p-value = 0.0001
- Critical Value (tc) = 1.645

**Conclusion:** 🎯
We reject the null hypothesis at the 5% significance level. The mean age of mothers in North Carolina is **greater than 25 years**!

---

### 2. **Mean Weeks of Gestation** 🤰
**Hypothesis:**
- **Null Hypothesis (H0):** μ ≥ 39 (The mean weeks of gestation is greater than or equal to 39 weeks)
- **Alternative Hypothesis (Ha):** μ < 39 (The mean weeks of gestation is less than 39 weeks)

**Test Results:**
- t-statistic = -4.9583
- p-value = 0.0001
- Critical Value (tc) = 1.645

**Conclusion:** 🎯
We reject the null hypothesis at the 95% confidence interval. The average **gestation period** in North Carolina is **less than 39 weeks**!

---

### 3. **Mean Weight of Babies Born** 👶
**Hypothesis:**
- **Null Hypothesis (H0):** μ ≤ 112 (The mean weight of babies is less than or equal to 112 ounces or 7 lbs)
- **Alternative Hypothesis (Ha):** μ > 112 (The mean weight of babies is greater than 112 ounces)

**Test Results:**
- t-statistic = 7.465
- p-value = 0.0001
- Critical Value (tc) = 1.645

**Conclusion:** 🎯
We reject the null hypothesis at the 5% significance level. The average **birth weight** is **greater than 7 lbs** (112 ounces).

---

### 4. **Birth Weight Comparison: Smoking vs Non-Smoking Mothers** 🚭
**Hypothesis:**
- **Null Hypothesis (H0):** μsmoking ≥ μnon-smoking (The mean birth weight of babies born to smoking mothers is greater than or equal to that of non-smoking mothers)
- **Alternative Hypothesis (Ha):** μsmoking < μnon-smoking (The mean birth weight of babies born to smoking mothers is less than that of non-smoking mothers)

**Test Results:**
- t-statistic = 5.07
- p-value = 0.0001
- Critical Value (tc) = 1.96

**Conclusion:** 🎯
We reject the null hypothesis at the 5% significance level. Babies born to **smoking mothers** have **lower birth weights** than those born to **non-smoking mothers**.

---

### 5. **Percentage of Low Birth Weight Children** 💔
**Hypothesis:**
- **Null Hypothesis (H0):** p ≤ 0.06 (The percentage of low birth weight children is less than or equal to 6%)
- **Alternative Hypothesis (Ha):** p > 0.06 (The percentage of low birth weight children is greater than 6%)

**Test Results:**
- z-statistic = 3.872
- p-value = 0.0001
- Critical Value (zc) = 1.96

**Conclusion:** 🎯
We reject the null hypothesis at the 0.025 significance level. The percentage of **low birth weight** children is **greater than 6%** in North Carolina!

---

### 6. **Percentage of Mothers Who Smoke** 🚬
**Hypothesis:**
- **Null Hypothesis (H0):** p ≤ 0.10 (The percentage of mothers who smoke is less than or equal to 10%)
- **Alternative Hypothesis (Ha):** p > 0.10 (The percentage of mothers who smoke is greater than 10%)

**Test Results:**
- z-statistic = 5.7806
- p-value = 0.0001
- Critical Value (zc) = 1.96

**Conclusion:** 🎯
We reject the null hypothesis at the 5% significance level. The percentage of **mothers who smoke** in North Carolina is **greater than 10%**!

---

### 7. **Low Birth Weight Comparison for Smoking vs Non-Smoking Mothers** 🚭💔🤰
**Hypothesis:**
- **Null Hypothesis (H0):** psmoking = pnon-smoking (The percentage of low birth weight for smoking mothers is the same as for non-smoking mothers)
- **Alternative Hypothesis (Ha):** psmoking ≠ pnon-smoking (The percentage of low birth weight for smoking mothers is different from that for non-smoking mothers)

**Test Results:**
- p-value = 0.0197
- z-statistic = -2.3325

**Conclusion:** 🎯
We reject the null hypothesis at the 5% significance level. The **percentage of low birth weight** for **smoking mothers** is **significantly different** from that for non-smoking mothers.

---

### 8. **Low Birth Weight for Smoking Mothers vs Non-Smoking Mothers (Further Comparison)** 🚭💔🤰
**Hypothesis:**
- **Null Hypothesis (H0):** psmoking ≥ pnon-smoking (The percentage of low birth weight for smoking mothers is greater than or equal to that for non-smoking mothers)
- **Alternative Hypothesis (Ha):** psmoking < pnon-smoking (The percentage of low birth weight for smoking mothers is lower than for non-smoking mothers)

**Test Results:**
- p-value = 0.0098
- z-statistic = 2.3325

**Conclusion:** 🎯
We reject the null hypothesis at the 0.025 significance level. The **percentage of low birth weight** for **smoking mothers** is **lower** than for non-smoking mothers.

---

### 9. **Low Birth Weight for Mothers Who Drank Alcohol vs Did Not Drink Alcohol** 🍷💔
**Hypothesis:**
- **Null Hypothesis (H0):** pnon-alcohol ≥ palcohol (The percentage of low birth weight for mothers who did not drink alcohol is greater than or equal to the percentage of low birth weight for mothers who drank alcohol)
- **Alternative Hypothesis (Ha):** pnon-alcohol < palcohol (The percentage of low birth weight for mothers who did not drink alcohol is lower than for mothers who drank alcohol)

**Test Results:**
- p-value = 0.3396
- z-statistic = 0.4136

**Conclusion:** 🎯
We **fail to reject** the null hypothesis at the 0.025 significance level. There is no strong evidence to show that **alcohol consumption** impacts the **rate of low birth weight**.

---


## 📂 Project Report

For a detailed breakdown of the project, including design methodologies, implementation details, and test results, refer to the full project report:

📄 **[SAS Birth Statistics Project Report](docs/SASProject.pdf)**

