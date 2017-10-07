# PIMA

Applying below listed Machine Learning Algorithms to the Famous PIMA dataset available at UCI ML Repository:

https://archive.ics.uci.edu/ml/machine-learning-databases/pima-indians-diabetes/pima-indians-diabetes.data

1. Naive-Bayes Gaussian Classifier
2. Naive-Bayes Multinomial Classifier
3. Parallel Co-ordinated plots
4. KNearest Neighbours
5. Logistic Regression

Steps are described as below with the insights from each step.

>> PIMA Diabetes Dataset is downloaded from the UCI portal & Header is added.

>> Checking correlation of all the 9 features by plotting against each other.

>> Splitting Features from Target 

>> Converting Data to array for computational needs such that the Gaussian - NB can be applied.

>> Gaussian NB gives a 76% accuracy with Specificity = 0.61 & Sensitivity = 0.84

>> Loading Libraries to apply Multinomial Naive-Bayes which gives 89% accuracy. 

>> Normalizing Data to create Parallel Coordinated plot, which unearths that the Higher values of Plasma_Glucose_Conc,Tristolic_Blood_Pressure & BMI leads to higgher chances of Diabetes.

>> Applying K-Nearest Neighbours algorithm to predict the acuracy, gives an 80% accuracy which is lower than the Multinomial Naive-Bayes.

>> Also checking the data on Traditionaly used Logistic Regression used to make prediction in Binary Outcomes 0/1.

>> Logistic Regressin gives an Accuracy of 74% only However the Miss-classification Error = 0.25 , Sensitivity = 0.49, Specificity = 0.80.

>> Exploring further results with altering the prediction probability & compairing results with new predictions.
