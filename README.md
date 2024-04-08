# computer-intelligence-wind-power-prediction

## Description
In this research project, the primary motivation is to address the critical need for accurate wind energy prediction. To achieve this, i employ several algorithms to investigate the performance of each algorithm in predicting wind energy output based on meteorological data, including date, wind speed, direction, and temperature.

## Datasets
This project utilises two key datasets from Kaggle for wind energy analysis. The first dataset, derived from "T1.csv," originally contains 42,764 data points, which, after preprocessing to remove null values in the "ActivePower" column, is reduced to 39,267 entries. It includes timestamps, wind speed, power output, theoretical power, and wind direction. The second dataset, "TexasTurbine.csv," consists of 8,760 entries with a newly added "Month" column, offering detailed insights into turbine performance and environmental conditions. Both datasets are integral to the project's focus on wind energy prediction modelling.

## ML and DL
Utilized Decision Tree and Radial Basis Function Networks (RBFNs)

## Performance Evaluation 
### Dataset 1 (T1.csv)

Decision Tree:

Best Parameters: {'max_depth': 10, 'min_samples_leaf': 4, 'min_samples_split': 10}

Decision Tree Accuracy: 0.9531241003097914

MAE on the validation set (Dataset 1): 122.47430807650471

MAE on the test set (Dataset 1): 121.07598970020597

MSE on the validation set (Dataset 1): 75625.51954320802

MSE on the test set (Dataset 1): 74739.55057405189

RMSE on the validation set (Dataset 1): 275.0009446223922

RMSE on the test set (Dataset 1): 273.3853517912982

![image](https://github.com/esmond09/computer-intelligence-wind-power-prediction/assets/130723274/4f6be1d8-81ee-48a6-8434-e671c2f6ece5)

Radial Basis Function Networks (RBFNs):

Best Parameters: {'bernoullirbm__n_components': 15, 'kmeans__n_clusters': 10, 'linearregression__fit_intercept': True, 'linearregression__n_jobs': 1, 'linearregression__positive': False}

RBFN Accuracy: 0.9499952727782828

(Dataset 1) MAE on the validation set : 138.6224361059687

(Dataset 1) MAE on the test set : 138.6224361059687

(Dataset 1) MSE on the validation set: 75150.97992596653

(Dataset 1) MSE on the test set: 79728.19431367333

(Dataset 1) RMSE on the validation set: 274.1367905370721

(Dataset 1) RMSE on the test set: 282.3618145459356

![image](https://github.com/esmond09/computer-intelligence-wind-power-prediction/assets/130723274/e81e60fe-e331-453a-a817-a3201edd284f)

### Dataset 2 (TexasTurbine.csv)

Decision Tree:

Best Parameters: {'max_depth': None, 'min_samples_leaf': 1, 'min_samples_split': 2}

Decision Tree Accuracy (Dataset 2): 0.9998731952977928

MAE on the validation set (Dataset 2): 5.460184614916283

MAE on the test set (Dataset 2): 5.770434204718418

MSE on the validation set (Dataset 2): 88.42479850319161

MSE on the test set (Dataset 2): 94.67953068804171

RMSE on the validation set (Dataset 2): 9.403446097213065

RMSE on the test set (Dataset 2): 9.730340728260327

![image](https://github.com/esmond09/computer-intelligence-wind-power-prediction/assets/130723274/f1007753-676a-46a5-9bc4-d86a04f1902d)

Radial Basis Function Networks (RBFNs):

Best Parameters: {'bernoullirbm__n_components': 10, 'kmeans__n_clusters': 15, 'linearregression__fit_intercept': True, 'linearregression__n_jobs': 1, 'linearregression__positive': False}

(Dataset 2) RBFN Accuracy: -9.439533522392907e-06

(Dataset 2) MAE on the validation set : 731.1472406370551

(Dataset 2) MAE on the test set : 724.9467995190071

(Dataset 2) MSE on the validation set: 746531.725885798

(Dataset 2) MSE on the test set: 746663.3553067062

(Dataset 2) RMSE on the validation set: 864.0206744550723

(Dataset 2) RMSE on the test set: 864.0968437083346

![image](https://github.com/esmond09/computer-intelligence-wind-power-prediction/assets/130723274/487dd680-f907-4619-9552-2c98ccdc3333)

