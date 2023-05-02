#  Logisitic Regression

Logistic regression is a type of supervised learning algorithm used for binary classification tasks, where the goal is to predict the probability of an instance belonging to one of two possible classes. Logistic regression models the relationship between a set of input features (also known as independent variables or predictors) and a binary output variable (also known as the dependent variable or response variable) by estimating the probability of the output variable being equal to one of the two classes.
  
![plot](/Logistic Regression.png)

## Dataset
The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has 10-year risk of future coronary heart disease (CHD).The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.

**Information on current medical condition**
- Tot Chol: total cholesterol level
- Sys BP: systolic blood pressure
- Dia BP: diastolic blood pressure
- BMI: Body Mass Index
- Heart Rate: heart rate - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.
- Glucose: glucose level
- Target variable to predict
- TenYearCHD: 10 year risk of coronary heart disease (binary: “1:Yes”, “0:No”)
The dataset is a public dataset describe some variables influencing medical insurance charge. The dataset has 8 columns and 1338 rows.



## Package used
Pandas [https://pandas.pydata.org/](https://pandas.pydata.org/)  
Matplotlib [https://matplotlib.org/](https://matplotlib.org/)  
Numpy [https://numpy.org/](https://numpy.org/)  
Seaborn [https://seaborn.pydata.org/](https://seaborn.pydata.org/)  
Scikit-learn [https://scikit-learn.org/](https://scikit-learn.org/)