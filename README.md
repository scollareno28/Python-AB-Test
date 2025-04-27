# 🧪 A/B Test Analysis

## 📋 Project Overview

This project analyzes an A/B test experiment to determine if there is a statistically significant difference between two groups: **Group A** (control) and **Group B** (treatment).

Using statistical testing methods, the analysis explores whether the new variant improves user behavior compared to the control, helping businesses make informed decisions.

The analysis focuses on understanding conversion rates, comparing means, running hypothesis tests, and making data-driven recommendations.

---

## 🛠️ Project Workflow

1. **Data Loading**
   - Imported user interaction data from a CSV file.
   - Key variables included group assignment (A or B) and user behavior (e.g., conversion outcome).

2. **Data Cleaning**
   - Checked for and handled missing values.
   - Ensured correct data types (e.g., categorical variables).

3. **Exploratory Data Analysis (EDA)**
   - Analyzed the number of users in each group.
   - Calculated conversion rates for Group A and Group B.
   - Visualized distributions and summarized statistics.

4. **Statistical Hypothesis Testing**
   - Set up null and alternative hypotheses:
     - **Null Hypothesis (H₀):** No difference between Group A and Group B.
     - **Alternative Hypothesis (H₁):** A difference exists.
   - Conducted:
     - **Two-proportion z-test** for comparing conversion rates.
     - **p-value interpretation** to assess significance.

5. **Conclusion and Recommendations**
   - Based on p-values and confidence intervals, determined whether to reject or fail to reject the null hypothesis.
   - Provided actionable insights for business decision-making.

---

## 📊 Key Results


**Outcome:**
- If p-value < 0.05: Reject the null hypothesis — statistically significant difference detected.
- If p-value >= 0.05: Fail to reject the null hypothesis — no statistically significant difference.

📢 **Recommendation:** Overall we are rejecting the null hypothesis however it depends on the variable you are trying to measure.  

---

## 📈 Future Improvements

- Perform **segmented A/B testing** (e.g., by device type, user demographics).
- Use **Bayesian A/B Testing** to complement traditional hypothesis testing.
- Extend testing duration to capture **long-term effects**.
- Analyze **secondary metrics** (e.g., time on site, customer satisfaction).
- Conduct **power analysis** before starting the experiment to ensure adequate sample size.

---

## 🧪 Technologies Used

- **Python 3.10+**
- **Pandas** (data handling)
- **NumPy** (numerical calculations)
- **Matplotlib**, **Seaborn** (visualizations)
- **Scipy.stats** (hypothesis testing)

---

