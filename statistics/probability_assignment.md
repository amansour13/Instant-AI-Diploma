# 1. Types of Statistics Tests

## 1. Parametric Tests: make assumptions (normal distribution) about population distribution and require continous data
### T-test: compare means of 2 groups
#### EX: check if group A has **different averages** scores of group B

### Paired T-test: compare between the mean of the same group **before and after** an event
#### Ex: testing if a new method is significant in any.

### ANOVA: compare the means of 3 or more groups
#### EX: testing a 3 different diet strategies.

### Z-test: similar to T-test (comparing 2 means of different groups) but for large samples (n > 30)
#### EX: determine if average heights is more than 170 cm.

### Linear Regression: measure a linear relationship between 2 variables (usaully predicator and outcome)
#### EX: house price and area of the building.

### Correlation: measure the strength and direction of a linear relationship between 2 continous variables 
#### EX: correaltion between study time and exam scores.

## 2. Non-Parametric: these tests don't assume normal distribution and used for ordinal, ranked and small sample data
### EX: 
### - Mann-Whitney U Test (like T-test)
### - Wilcoxon Signed-Rank Test (like Paired T-test)
### - Kruskal-Wallis Test (like ANOVA)
### - Spearman’s Rank Correlation (like Correlation)

## 3. Categorical Data Tests: these analyze frequency and proportions in categorical data (nominal)
### Chi-Square Test: Test between 2 categorical variables
#### EX: Determine if gender affects customer voting prefrences.

### Fisher’s Exact Test: similar to Chi-Square but for small samples.

### McNemar’s Test: test paired categorical data (before and after)
#### EX: Evaluating Website redesign based on user preferences.

# 2. The difference between type 1 error and type 2 error
## type 1 error (alpha)
### called False Positive 
### occurs when the null hypothesis (H₀) is true, but we incorrectly reject it
#### Ex: a medical test indicates that a healthy person has a disease


## type 2 error (beta)
### called False Negative 
### occurs when the null hypothesis (H₀) is false, but we fail to reject it
#### Ex: a medical test indicates that a sick person has not a disease


# 3. The Naive bayes and conditional probability
## Conditional Probability: means that a what is the probability of A happens given that probability of B.
### Formula: P(A|B) = P(A and B) / P(B)
### Ex: what is the probability of students "pass" given that they "study"
### P(pass|study) = P(pass and study) / P(study)

## Naive Bayes : it is a machine learning algorithm based on conditional probability and it assume that all the features are indpendent.
### used in classification problems
### Formula : P(A|B) = (P(B|A) * P(A)) / P(B)
### EX: used to detect if a word is a spam or not (P(Spam | Word))



# 4. What is the Central limit Theory
## CLT: it is a probability theory which states that the distribution of a sample will approximate a normal distribution (i.e., a bell curve) as the sample size becomes larger, regardless of the population's actual distribution shape.
### the inputs:
### - mean
### - standard deviation (need to be 30 or more)

### the outputs:
### - mean = same input mean
### - standard deviation = standard deviation / sqrt(n) (where n is the sample size)

