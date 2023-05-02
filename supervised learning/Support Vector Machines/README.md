#  Support Vector Machine

Support Vector Machine is a popular type of supervised learning algorithm used for classification and regression analysis.

In SVM, the goal is to find the hyperplane that best separates the different classes in the input feature space. A hyperplane is a decision boundary that divides the feature space into two regions corresponding to the different classes. The SVM algorithm aims to find the hyperplane that maximizes the margin between the closest points of the two classes, known as support vectors. The margin is the distance between the hyperplane and the support vectors, and it represents the level of confidence that the algorithm has in its predictions.
  


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