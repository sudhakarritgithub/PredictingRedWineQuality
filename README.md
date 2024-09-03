# Predicting Red Wine Quality
# Wine Quality Dataset for Machine Learning

This dataset, known as the Wine Quality dataset, is a valuable resource for exploring machine learning techniques and conducting predictive analysis. The dataset was compiled by Paulo Cortez, Antonio Cerdeira, Fernando Almeida, Telmo Matos, and Jose Reis in 2009, with contributions from CVRVV (Vinho Verde Regional Wine Commission). It has been used to model wine preferences by mining data from physicochemical properties, resulting in a regression approach to predict wine quality based on sensory data.

## Background

The dataset comprises two distinct subsets, each representing red and white variants of the Portuguese "Vinho Verde" wine. Although certain details like grape types, wine brand, and selling prices are omitted due to privacy and logistic constraints, it still offers a wealth of information for analysis. The goal is to predict wine quality ratings, which are scored between 0 (very bad) and 10 (very excellent), using a set of physicochemical attributes as inputs.

## Dataset Details

- **Number of Instances:** Red Wine - 1599; White Wine - 4898
- **Number of Attributes:** 11 input attributes + 1 output attribute

### Input Attributes (Physicochemical Tests)

1. Fixed Acidity
2. Volatile Acidity
3. Citric Acid
4. Residual Sugar
5. Chlorides
6. Free Sulfur Dioxide
7. Total Sulfur Dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol

### Output Attribute (Sensory Data)

12. Quality (Score between 0 and 10)

## Accessing the Dataset

For more details about the dataset, its creation, and its usage, refer to the original paper by Cortez et al. [here](https://archive.ics.uci.edu/ml/datasets/Wine+Quality).
# Red Wine Quality Prediction Models

I conducted a comprehensive analysis to predict red wine quality based on physicochemical attributes given in the dataset. Below are the results of the various models I developed:

## Model Performance Summary

| Model                           | R2 Score | Mean Squared Error |
|---------------------------------|----------|--------------------|
| Multiple Linear Regression      | 0.5151   | 0.5866             |
| Support Vector Regression (SVR) | 0.7041   | 0.3579             |
| Decision Tree                   | 0.5889   | 0.4973             |
| Random Forest                   | 0.7600   | 0.2904             |

## Insights and Observations

- The **Support Vector Regression (SVR)** model achieved the highest R2 score of 0.7041, indicating its strong predictive capability. However, it's important to note that this model was computationally expensive.
- The **Random Forest** model demonstrated impressive performance with an R2 score of 0.7600, outperforming other models and resulting in the lowest mean squared error (0.2904).
- The **Multiple Linear Regression** and **Decision Tree** models also showcased reasonable performance, with R2 scores of 0.5151 and 0.5889, respectively.

These results provide valuable insights into the predictive power of different models for red wine quality prediction.

## Conclusion

Through this project, I aimed to explore the relationships between physicochemical attributes and red wine quality. The results obtained from various models lay the foundation for optimizing predictions and enhancing our understanding of wine quality determinants.

[Dataset Source](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
