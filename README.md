# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

CODING AND OUTPUT:
       ![image](https://github.com/user-attachments/assets/16c21948-5678-4751-b1c3-d0956602a4a8)
       ![image](https://github.com/user-attachments/assets/a019a85c-4489-481e-ba02-f99f75706b01)
       ![image](https://github.com/user-attachments/assets/5dcb18ce-0ca8-4fd8-9d18-e2a52593dc7d)
       ![image](https://github.com/user-attachments/assets/25b753fd-a029-4655-a3ed-c0ec7ca11db5)
       ![image](https://github.com/user-attachments/assets/cc994823-cbd0-44e4-b841-5fe6e242e3d9)
       ![image](https://github.com/user-attachments/assets/f58cd2f0-f0a2-40e2-a51d-57a6678bb27e)
       ![image](https://github.com/user-attachments/assets/1c64292c-1e84-4a21-b9e5-a6b9c2c10a84)

# RESULT:
       Thus the given data is read and performed the Feature Scaling and Feature Selection process and saved the file
