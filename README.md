# Common hypothesis tests in Python

Hypothesis testing is essentially about calculating how certain we can be about an inference based on our sample.  
The most common process for calculating this has several steps:

1. Assume the inference is not true on the population — this is called the null hypothesis
2. Calculate the statistic of the inference on the sample
3. Understand the expected distribution of the sampling error around that statistic
4. Use that distribution to understand the maximum likelihood of your sample statistic being consistent with the null hypothesis
5. Use a chosen ‘likelihood cutoff’ — known as alpha — to make a binary decision on whether to accept the null hypothesis or reject it. The most commonly used value of alpha is 0.05. That is, we usually reject a null hypothesis if it renders the maximum likelihood of our sample statistic to be less than 1 in 20.

## Tests:
- Welch’s t-test
- Correlation test
- Chi-square test of difference in proportion
