# Analyzing-Salary-Trends-in-Baseball--SVR-and-SVM-Approach

## Support vector regression
<img src="https://github.com/KocHanim/Analyzing-Salary-Trends-in-Baseball--SVR-and-SVM-Approach/assets/115664157/07c85943-affa-4c09-9b5d-b653a73b616d" alt="images" align="right" width="500" height="350">
Support vector regression is a machine learning method that attempts to make predictions by grouping data on a hyperplane. 
This method can use different kernel functions depending on whether the data is linear or non-linear. 
Kernel functions transform the data into a higher dimensional space, increasing the fit between the hyperplane and the data. 
Support vector regression tries to maximise the largest marginal distance to the data. The margin is the smallest distance between the hyperplane and the data. 
Support vector regression can take different parameters depending on the distribution and noise of the data. 
These parameters determine the slope, shift and flexibility of the hyperplane. 
Support vector regression is an effective method for solving regression problems and can be applied in various fields[1][2]

## Parameter C
<img src="https://github.com/KocHanim/Analyzing-Salary-Trends-in-Baseball--SVR-and-SVM-Approach/assets/115664157/2e9b37bd-6d22-4f94-911b-9005e046afbf" alt="images" align="right" width="500" height="200">

Parameter C is a hyper-parameter that controls the complexity of the support vector regression model. 
Parameter C determines the error tolerance between the hyperplane and the data. 
The larger the C parameter, the less error the model accepts and the more it fits the data. 
This can increase the risk of the model overfitting. The smaller the C parameter, the more error the model accepts and the less it fits the data. 
This can increase the risk of the model underfitting. The C parameter affects the generalisation ability of the model. 
The C parameter can take different values depending on the distribution and noise of the data. 
Different methods can be used to determine the C parameter, such as cross-validation. 
The C parameter is important for optimising the performance and accuracy of the support vector regression model.[3]

## Project Details:


We find the best parameter C using Support Vector Regression. GridSearchCV and k-fold cross-validation methods were used in this process.(SVR.ipynb) The C parameter we obtained was used for Support Vector Machines for classification. Threshold value was found and prepared as 2 classes. 
Within the project, 2 estimation processes were performed as primitive C parameter and best C parameter. As a result of SVM, the primitive C parameter (1.0) achieved 71% success, while the best C parameter (0.5) achieved 74% success. 
The bottom graph shows the prediction and actual results.

<img src="https://github.com/KocHanim/Analyzing-Salary-Trends-in-Baseball--SVR-and-SVM-Approach/assets/115664157/28e4eb88-643f-43ee-80fe-55c7613ebb03" alt="images" align="center">


*Can you hear it? The noise of the future!*

# Author:
Rumeysa KOÇ

# References
[1] https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html

[2] https://www.mathworks.com/help/stats/understanding-support-vector-machine-regression.html

[3] https://medium.com/@rathodrutesh/what-is-parameter-c-in-support-vector-machine-regression-f75be9df98ec

