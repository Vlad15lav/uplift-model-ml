# uplift-model-ml
X5 Retail Group Uplift Model

This is the task of predicting customers who may be influenced by the company.
## Description
Test task for the Machine Learning course by SHIFT
[Kaggle Competition](https://www.kaggle.com/competitions/uplift-shift-23/overview)

The task uses the Class Transformation according to the condition of the task.

## Evalution
| Model       | Public Test                | Private Test |
| ------------- |:------------------:| -----:|
| LightGBM     | 0.04652    | 0.04919 |
| CatBoost + XGBoost + LightGBM + RF     | 0.05491 |   0.04506 |
