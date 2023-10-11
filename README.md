# Concrete-Compressive-Strength-Prediction_Machine-Learning_project

### About:

Concrete is the most important material in civil engineering. The concrete compressive strength is a highly nonlinear function of age and ingredients. The quality of concrete is determined by its compressive strength. In order to test for strength fluctuations as each raw material is changed, engineers must construct miniature concrete cylinders using various combinations of raw materials. It takes about a month to get accurate results and this approach is vulnerable to human error, and even a minor inaccuracy might result in a significant lengthening of the wait time.

Data science is the answer to this issue. In order to forecast compressive strength, we will study a dataset of concrete compressive strength and develop machine learning models. It could be possible to create a combination of elements that produces a high Strength by utilizing machine learning to anticipate the strength.


Please refer [*Concrete_Compressive_Strength_Prediction.ipynb*](https://github.com/ShivangiRastogi1/Concrete-Compressive-Strength-Prediction-Machine-Learning/blob/main/Concrete_Compressive_Strength_Prediction.ipynb.ipynb) for code.

## 1. Problem Statement
Predicting Compressive Strength of Concrete given its age and quantitative measurements of ingredients.

## 2. Data Description

The UC Irvin Machine Learning Repository is where the data comes from.
https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength

* Number of instances - 1030
* Number of Attributes - 9
  * Attribute breakdown - 8 quantitative inputs, 1 quantitative output

#### Attribute information
##### Inputs
* Cement (component 1) -- quantitative -- kg in a m3 mixture -- Input Variable
* Blast Furnace Slag (component 2) -- quantitative -- kg in a m3 mixture -- Input Variable
* Fly Ash (component 3) -- quantitative  -- kg in a m3 mixture -- Input Variable
* Water  (component 4) -- quantitative  -- kg in a m3 mixture -- Input Variable
* Superplasticizer (component 5) -- quantitative -- kg in a m3 mixture -- Input Variable
* Coarse Aggregate  (component 6) -- quantitative -- kg in a m3 mixture -- Input Variable
* Fine Aggregate (component 7)	 -- quantitative  -- kg in a m3 mixture -- Input Variable
* Age -- quantitative  -- Day (1~365) -- Input Variable

All above features measured in kg/$m^3$


##### Output
* Concrete compressive strength -- quantitative -- MPa -- Output Variable

  ## 3. Modelling and Evaluation

* Below Machine Learning Algorithms are used :
  * Linear regression
  * Lasso regression
  * Ridge regression
  * Decision Trees
  * Random Forests

* Metric - Since the target variable is a continuous variable, regression evaluation metric RMSE (Root Mean Squared Error) and R2 Score (Coefficient of Determination) have been used.

## 4. Results

#### Feature correlation
![Feature correlation](https://github.com/ShivangiRastogi1/Concrete-Compressive-Strength-Prediction-Machine-Learning/blob/main/imgs/corr.png)
#### Feature importance
![Feature importance](https://github.com/ShivangiRastogi1/Concrete-Compressive-Strength-Prediction-Machine-Learning/blob/main/imgs/feat_imp.png)
#### Final Comparison
![Final Comparison](https://github.com/ShivangiRastogi1/Concrete-Compressive-Strength-Prediction-Machine-Learning/blob/main/imgs/comparision.png)


## 5. References
1. https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength

Yeh,I-Cheng. (2007). Concrete Compressive Strength. UCI Machine Learning Repository. https://doi.org/10.24432/C5PK67.

