# 📊 Part A - Theoretical Foundation

## 📘 1. What is Statistical Distributions?

➡️ A statistical distribution describes how the values of a random variable are spread (or distributed) across possible outcomes.

---

## 📈 2. What is a Q-Q Plot and why is it used?

➡️ A Q-Q plot is a graphical tool to check whether a dataset follows a particular theoretical distribution (often the Normal distribution).

### 📌 Components:

• X-axis → Theoretical quantiles (from the chosen distribution).
• Y-axis → Sample quantiles (from your dataset).

### 📊 Interpretation:

✅ **Normal Data:** The points fall nearly along the diagonal line, meaning the data is approximately normally distributed.

❌ **Exponential Data vs Normal:** The points deviate strongly from the line, especially in the tails, showing that the exponential data is not normally distributed.

---

## 🔢 3. Difference between Discrete and Continuous Distribution?

### 🔹 Discrete Distribution

➡️ Definition: Deals with outcomes that are countable (finite or infinite but countable).

➡️ Probability: Each possible value has a specific probability.

### 📌 Common Discrete Distributions:

• Bernoulli (0 or 1, success/failure)
• Binomial (number of successes in n trials)
• Poisson (count of events in a fixed interval)

### 🔹 Continuous Distribution

➡️ Definition: Deals with outcomes that take values in a continuous range (uncountable).

➡️ Probability: Exact probability at one point = 0, but we measure probability over an interval.

### 📌 Common Continuous Distributions:

• Normal (Gaussian)
• Exponential
• Uniform (continuous range with equal chance)

---

## 🎯 4. What is Bernoulli Distribution?

➡️ A Bernoulli distribution is the simplest probability distribution.

It describes a random experiment with only two possible outcomes:

• ✅ Success (1) with probability p
• ❌ Failure (0) with probability 1 − p

---

## 🎲 5. What is Binomial Distribution?

➡️ The Binomial distribution is an extension of Bernoulli.

It models the probability of getting k successes in n independent Bernoulli trials.

📌 A Bernoulli distribution is a special case of the Binomial distribution when n = 1.

**Bernoulli(p) = Binomial(n = 1, p)**

---

## 📉 6. Explain Log-Normal Distribution?

➡️ A Log-Normal Distribution is a probability distribution in which the logarithm of the variable follows a normal distribution.

In simple terms, if taking the natural logarithm (log) of a dataset makes it normally distributed, then the original data follows a Log-Normal Distribution.

### 📌 Key Characteristics:

• Values are always positive (greater than 0).
• The distribution is right-skewed (long tail on the right side).
• Most observations are small, while a few observations can be very large.
• Commonly used for financial and transaction data.

---

## 📊 7. Explain Power Law Distribution?

➡️ A Power Law Distribution is a probability distribution where small values occur very frequently, while very large values occur rarely but have a significant impact.

### 📌 Key Characteristics:

• Highly right-skewed distribution.
• Most observations are small.
• A few observations are extremely large.
• Has a heavy tail, meaning large values are more common than in a Normal Distribution.
• Often follows the 80/20 rule (Pareto Principle).

---

## 🔄 8. What is Box-Cox Transform?

➡️ A Box-Cox Transformation is a statistical technique used to reduce skewness, stabilize variance, and make data closer to a normal distribution.

### 📌 Why is it used?

• Reduces right-skewness or left-skewness.
• Makes data more normally distributed.
• Improves the performance of statistical models and hypothesis tests.
• Stabilizes variance across the dataset.

### 📌 How does it work?

Box-Cox automatically finds the best value of λ (lambda) and transforms the data accordingly.

• λ = 1 → No transformation
• λ = 0 → Log transformation
• λ = 0.5 → Square root transformation
• λ = -1 → Reciprocal transformation

---

## 🎯 9. Explain Poisson Distribution with an Example?

➡️ A Poisson Distribution is a probability distribution used to model the number of times an event occurs in a fixed interval of time, space, or area.

### 📌 Conditions:

• Events occur independently.
• Events happen at a constant average rate.
• We want to count the number of occurrences.

### 🏦 Example:

Suppose a bank receives 5 transactions per minute on average.

Question:
➡️ What is the probability that exactly 3 transactions occur in the next minute?

Where:
• λ (lambda) = 5
• x = 3

### 📌 Key Characteristics:

• Used for count data.
• Values are non-negative integers (0,1,2,3,...).
• Mean = Variance = λ (lambda).
• Suitable for rare or random events.

---

## 📏 10. What is Z-score Probability?

➡️ Z-score probability is the probability of a value occurring below, above, or between certain values in a Normal Distribution.

A Z-score tells us how many standard deviations a value is away from the mean.

### 📌 Why is Z-Score Useful?

• Detects outliers.
• Compares values from different datasets.
• Calculates probabilities in a Normal Distribution.
• Standardizes data for machine learning and statistical analysis.

---

## 📈 11. Differentiate Probability Density Function (PDF) and Cumulative Distribution Function (CDF)?

### 🔹 Probability Density Function (PDF)

➡️ The PDF describes the likelihood of a random variable taking on a specific value.

• For continuous variables, the probability of any exact value is 0.
• The area under the PDF curve gives probability.

### 📌 Properties:

• Always ≥ 0
• Total area under curve = 1

### 🔹 Cumulative Distribution Function (CDF)

➡️ The CDF gives the probability that a random variable X is less than or equal to a certain value x.

• It is obtained by integrating the PDF from −∞ to x.

### 📌 Properties:

• Increases from 0 → 1
• Non-decreasing function
• Smooth for continuous distributions
