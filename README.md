# Predictive Modeling with Linear Regression

Linear regression is a fundamental parametric model in statistical learning, pivotal for predictive analytics. In this project, we explore three variants of linear regression models: ordinary least squares (OLS), ridge regression, and lasso regression. 

## Introduction

We delve into the nuances of preprocessing techniques for enhancing the predictive accuracy of these models. Specifically, we focus on the impact of preprocessing on feature and outcome values.

## Preprocessing Procedures

### Outcome Values (𝑦)

For outcome values, we consider two preprocessing procedures:
1. **Keep**: Retain original numerical values.
2. **De-mean**: Shift the mean to zero by subtracting the mean of 𝑦 from all outcome values.

### Feature Values

- **Continuous-valued Features (x_continue)**: Standardize feature values by subtracting the mean and dividing by their standard deviation.
- **Binary Features (x_binary)**: No standardization is typically applied.

## Dataset

We utilize a dataset comprising 44 features collected from a social media platform, aiming to predict the number of people who engaged with a post. Features include metrics such as likes, reach, and post type.

## Cases for Evaluation

We evaluate the performance of each model (OLS, Ridge, Lasso) across different preprocessing scenarios:

1. **Case 1: ymean method**
2. **Case 2A: OLS with original features and outcomes**
3. **Case 2B: OLS with original features and de-meaned outcomes**
4. **Case 2C: OLS with standardized features and de-meaned outcomes**
5. **Case 3A to 3D: Ridge regression with varying regularization coefficients**
6. **Case 4: Lasso regression with varying regularization coefficients**

## Questions

### Q1: Exploratory Analysis
- Provide summary statistics and visualizations of key variables.
- Discuss dataset characteristics.

### Q2 to Q11: Model Evaluation
- Conduct prediction models based on each case.
- Compute test RMSE for evaluation.
- Compare and discuss findings across all cases.

## Conclusion

Summarize the best RMSE of all cases and provide insights into the optimal preprocessing strategies for feature and outcome values.


