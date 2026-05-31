# 📊 Part A - Theoretical Foundation

## 📘 1. What is a Inferential Statistics?
* ➡️ Inferential Statistics is the branch of statistics that allows us to make predictions or draw conclusions about a larger group (called a population) by analyzing a smaller sample of data taken from it.

---

## 🧩 2. What is a hypothesis Testing and its components?
* ➡️ Hypothesis Testing is a statistical method used to make decisions about population parameters based on sample data.
* ➡️ **In simple terms:** It helps you determine whether an assumption (hypothesis) about a population is true or not.

### 📌 Components of Hypothesis Testing:

* ❌ **1. Null Hypothesis ($H_0$)**
  * • It is the default or initial claim.
  * • It assumes no effect, no difference, or status quo.
  * 📝 *Example:* $H_0: \mu = 10$ (The average battery life is 10 hours)

* 🎯 **2. Alternate Hypothesis ($H_1$ or $H_a$)**
  * • It is what you want to prove or test.
  * • It represents a change, an effect, or a difference.
  * 📝 *Example:* $H_1: \mu \neq 10$ (The average battery life is not 10 hours)

---

## 📏 3. Explain confidence Interval and Critical Value.

### 🔲 Confidence Interval:
* ➡️ A Confidence Interval gives a range of values where we believe the true population parameter lies, with a given level of confidence (e.g., 95%).
* 📌 **Formula:** $$\text{CI} = \text{sample\_mean} \pm z \cdot (\text{standard\_error})$$
  * • $z = 1.96$ for 95% confidence
  * • $\text{standard\_error} = \frac{s}{\sqrt{n}}$

### 🔲 Critical Value:
* ➡️ A critical value is the cutoff point in a hypothesis test that separates the rejection region from the non-rejection region.
* ➡️ It is determined by the significance level ($\alpha$) and the type of test being performed (Z-test, t-test, one-tailed, or two-tailed).
* 📝 *Example:* For a two-tailed Z-test with $\alpha = 0.05$, the critical values are: $$z = \pm 1.96$$
  * ✅ If the calculated Z-score is greater than 1.96 or less than -1.96 $\rightarrow$ **Reject $H_0$**
  * ❌ If the calculated Z-score lies between -1.96 and +1.96 $\rightarrow$ **Fail to reject $H_0$**

---

## 🧠 4. Define p-value?
* ➡️ The P-value is the probability of obtaining results at least as extreme as the observed results, under the assumption that the null hypothesis ($H_0$) is true.
  * 🟢 $\le \alpha$ (e.g., 0.05) = **Reject the null hypothesis (Significant)**
  * 🔴 $> \alpha$ = **Fail to reject the null hypothesis (Not Significant)**

---

## ⚠️ 5. Differentiate Type I and Type II errors?

### 🚫 Type I Error — False Positive
* • **Definition:** Rejecting a true null hypothesis.
* • You say something is significant when it’s not.
* 📝 *Example:* A medical test says a healthy person has a disease.

### 🚫 Type II Error — False Negative
* • **Definition:** Failing to reject a false null hypothesis.
* • You miss something that’s actually significant.
* 📝 *Example:* A medical test fails to detect a disease in a sick person.

---

## 🧪 6. Brief descriptions of z-test, t-test, chi-square test, and ANOVA test?

### 🔹 z-test (One Sample):
* ➡️ A Z-test is a statistical method used to determine whether there is a significant difference between sample data and a population (or between two samples). It helps answer the question: *“Is this difference real, or is it just due to random chance?”*
* 📌 **What Does a Z-Test Tell Us?**
  * A Z-test gives us a Z-score, which measures how many standard deviations the sample is away from the population mean (or another sample).
  * • A high absolute Z-score means the result is far from the expected average.
  * • It helps calculate a p-value, which quantifies how likely it is that the observed result occurred by random chance.

### 🔹 z-test (Two Sample):
* ➡️ A two-sample z-test is used to compare the means of two independent populations when population variances are known (or large samples, $n > 30$).
* 📌 **When to Use Two-Sample Z-Test?**
  * • Large sample sizes ($n > 30$)
  * • Population variances known or approximated well
  * • Independent samples

### 🔹 t-test (One Sample):
* ➡️ A one-sample t-test is used when we want to determine whether the mean of a sample is significantly different from a known or hypothesized population mean — especially when population standard deviation ($\sigma$) is unknown and sample size is small ($n < 30$).

### 🔹 t-test (Two Sample):
* ➡️ A two-sample t-test (also known as an independent t-test) is used to determine whether two independent samples have significantly different means.

### 🔹 Chi-Square Test:
* ➡️ The Chi-Square Test is a statistical test used to determine if there's a significant association between two categorical variables, or whether a categorical dataset fits a certain expected distribution.
* 📌 **Types of Chi-Square Tests:**
  1. **Chi-Square Goodness of Fit Test:** Tests if observed frequencies match expected frequencies (1 variable).
  2. **Chi-Square Test of Independence:** Tests if two categorical variables are independent (2 variables, contingency table).

### 🔹 ANOVA Test:
* ➡️ ANOVA (Analysis of Variance) is a statistical method used to compare the means of three or more groups to determine if at least one group mean is different from the others.
* 📌 **When to Use ANOVA?**
  * • Compare $>2$ group means = Eg. Test scores of 3 teaching methods
  * • A/B testing = Compare results across multiple experiments
  * • Feature impact testing = Check if a categorical variable affects output
* 📌 **Step of ANOVA test:**
  1. Group Means and Overall Mean
  2. SSB (Sum of square between)
  3. SSW (Sum of square within)
  4. Degree of freedom (between and within)
  5. MSB (Mean of square between)
  6. MSW (Mean of square within)
  7. F-ratio

---

## 📉 7. What is a Covariance?
* ➡️ Covariance measures how two variables change together.
  * • If both increase together $\rightarrow$ **Positive covariance**
  * • If one increases while the other decreases $\rightarrow$ **Negative covariance**
  * • If no pattern $\rightarrow$ **Covariance is zero or near-zero**

* 📊 **Positive Covariance (Left)**
  * • As X increases, Y also increases.
  * • Points form an upward-sloping pattern.
  * • $\text{Covariance} > 0$
* 📊 **Negative Covariance (Middle)**
  * • As X increases, Y decreases.
  * • Points form a downward-sloping pattern.
  * • $\text{Covariance} < 0$
* 📊 **No Covariance (Right)**
  * • No clear pattern between X and Y.
  * • $\text{Covariance} \approx 0$ (random scatter)

---

## 📈 8. What is a Correlation?
* ➡️ Correlation is a statistical measure that shows the strength and direction of the relationship between two variables.

### 📌 Correlation Types: Pearson and Spearman

#### 🔗 1. Pearson Correlation (r):
* ➡️ Pearson Correlation measures the linear relationship between two continuous numerical variables.
* 📌 **When to Use?**
  * • Data is numerical (interval or ratio scale).
  * • Relationship is linear (straight-line relationship).
  * • Data is approximately normally distributed.
* 📌 **Interpretation:**
  * • $r = +1$ $\rightarrow$ Perfect Positive Correlation
  * • $r = 0$ $\rightarrow$ No Correlation
  * • $r = -1$ $\rightarrow$ Perfect Negative Correlation

#### 🔗 2. Spearman Correlation ($\rho$ or $r_s$):
* ➡️ Spearman Correlation measures the relationship between two variables using their ranks rather than actual values.
* 📌 **When to Use?**
  * • Data is ordinal (ranked).
  * • Data is not normally distributed.
  * • Relationship is monotonic (consistently increasing or decreasing).