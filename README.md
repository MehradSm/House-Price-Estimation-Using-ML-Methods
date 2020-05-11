## House Price Estimation Using ML Methods

In this project we develop and implement different regression methods on datasets with a large number of both numerical and categorical features. We will explore linear regression as well as ensemble methods such as Gradient Boosting and Random Forest. We then evaluate each methods advantages along with their limitations such as overfitting. MATLAB has been used for the implementation. 

### Code
The code is divided to four categories:

1. The [Preprocessing.ipynb](https://github.com/MehradSm/House-Price-Estimation-Using-Machine-Learning-Methods/blob/master/Preprocessing.ipynb) Jupyter Notebook contains the code to preprocess the raw data. 
2. The [SimulateSpike.m](https://github.com/MehradSm/Modified-Spline-Regression/blob/master/SimulateSpike.m) file generates simulated neural spiking data
3. The [Hist.m](https://github.com/MehradSm/Modified-Spline-Regression/blob/master/Hist.m) file is to build design matrix for multiplicative hisory model
4. The [Indicator.m](https://github.com/MehradSm/Modified-Spline-Regression/blob/master/Indicator.m), [RaisedCos.m](https://github.com/MehradSm/Modified-Spline-Regression/blob/master/RaisedCos.m), [CardinalSpline.m](https://github.com/MehradSm/Modified-Spline-Regression/blob/master/CardinalSpline.m) and [ModifiedCardinalSpline.m](https://github.com/MehradSm/Modified-Spline-Regression/blob/master/ModifiedCardinalSpline.m) are four basis functions that used for point process generalizes linear model (GLM). 

To run the model, you should clone all the files and run [main.m](https://github.com/MehradSm/Modified-Spline-Regression/blob/master/main.m) file. 

