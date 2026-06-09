README – Spread Locator Dataset Statistical Analysis
📌 Project Overview

This project focuses on analyzing transaction data from the Spread Locator Dataset using statistical distributions, probability concepts, and data transformation techniques. The goal is to understand transaction behavior, identify patterns in transaction amounts and counts, evaluate probability distributions, assess normality, and apply transformations to improve data quality for further analysis.

📂 Dataset Description

The dataset contains transaction-related information such as:

Transaction Status
Transaction Count
Transaction Amount

These variables are used to perform probability analysis, distribution modeling, and statistical evaluation.

🎲 Bernoulli Distribution Analysis

The Bernoulli Distribution was used to calculate the probability of successful transactions. Since transaction status has only two possible outcomes (Success or Failure), it is an ideal use case for Bernoulli modeling.

Purpose
Determine the likelihood of a successful transaction.
Convert transaction outcomes into binary values for probability calculation.
Outcome

The analysis provided the overall success probability of transactions in the dataset.

🎯 Binomial Distribution Analysis

The Binomial Distribution was used to simulate transaction outcomes across multiple trials using the success probability obtained from the Bernoulli analysis.

Purpose
Model repeated transaction attempts.
Estimate the number of successful transactions within a fixed number of trials.
Outcome

Generated simulated transaction scenarios and helped understand the expected number of successful transactions over multiple attempts.

📈 Poisson Distribution Analysis

The Poisson Distribution was applied to model transaction frequency based on the average transaction count.

Purpose
Analyze how frequently transactions occur.
Estimate the probability of observing a certain number of transactions in a given period.
Outcome

Provided insights into transaction occurrence patterns and expected transaction volumes.

💰 Log-Normal Distribution Analysis

Transaction amounts were analyzed using a Log-Normal Distribution because financial data often exhibits right-skewed behavior.

Purpose
Examine the distribution pattern of transaction amounts.
Determine whether transaction values follow a log-normal structure.
Outcome

The analysis identified the characteristics of transaction amount distribution and helped understand spending behavior.

⚡ Power-Law Distribution Analysis

A Power-Law Distribution was fitted to transaction amounts to investigate the presence of heavy-tailed behavior.

Purpose
Identify whether a small number of transactions contribute disproportionately large values.
Analyze extreme transaction patterns.
Outcome

The analysis provided insights into rare but high-value transactions and the overall concentration of transaction amounts.

📉 Q-Q Plot Analysis

A Quantile-Quantile (Q-Q) Plot was used to evaluate whether transaction amounts follow a normal distribution.

Purpose
Compare observed data with a theoretical normal distribution.
Assess normality assumptions.
Outcome

The plot helped determine whether transaction amounts are normally distributed or significantly skewed.

🔄 Box-Cox Transformation

The Box-Cox Transformation was applied to positive transaction amounts.

Purpose
Reduce skewness in the data.
Improve normality.
Stabilize variance for better statistical analysis.
Outcome

The transformed data became more suitable for statistical modeling and hypothesis testing.

📏 Z-Score Analysis

Z-Scores were calculated for transaction amounts.

Purpose
Measure how far each transaction amount deviates from the mean.
Detect unusual observations and potential outliers.
Outcome

Helped identify transactions that were significantly higher or lower than typical transaction values.

🎯 Probability Analysis

A probability calculation was performed to estimate the likelihood of transaction amounts exceeding a specific threshold value.

Purpose
Assess the occurrence of high-value transactions.
Understand the risk and frequency of large transaction amounts.
Outcome

Provided the probability of observing transactions above the selected amount.

📚 Probability Density Function (PDF)

The Probability Density Function was used to visualize the distribution of transaction amounts.

Purpose
Understand where transaction values are most likely to occur.
Observe the shape and spread of the distribution.
Outcome

Provided a graphical representation of transaction amount density.

📖 Cumulative Distribution Function (CDF)

The Cumulative Distribution Function was used to evaluate cumulative probabilities.

Purpose
Determine the probability of transaction amounts being less than or equal to a specific value.
Understand cumulative transaction behavior.
Outcome

Provided a cumulative view of probability across transaction amounts.

📊 Visualizations Used

The project includes several visual analyses:

Q-Q Plot for normality assessment
PDF Curve for probability density visualization
CDF Curve for cumulative probability visualization

These visualizations improve understanding of data distribution and transaction behavior.

✅ Conclusion

This project successfully applied multiple statistical distributions and probability concepts to analyze transaction data. 
Bernoulli and Binomial distributions were used to study transaction success, Poisson distribution modeled transaction frequency, and Log-Normal and Power-Law distributions examined transaction amounts. 
Q-Q Plot and Box-Cox Transformation were utilized to assess and improve normality, while Z-Score analysis identified unusual observations. 
Finally, PDF and CDF visualizations provided a deeper understanding of probability distributions and transaction patterns, enabling more informed data-driven insights.