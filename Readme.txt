# PIMA

Applying below listed Machine Learning Algorithms to the Famous PIMA dataset available at UCI ML Repository:

https://archive.ics.uci.edu/ml/machine-learning-databases/pima-indians-diabetes/pima-indians-diabetes.data

1. Naive-Bayes Gaussian Classifier
2. Naive-Bayes Multinomial Classifier
3. Parallel Co-ordinated plots
4. KNearest Neighbours
5. Logistic Regression
6. Support Vector Machine
7. Various Boosting algo's

Steps are described as below with the insights from each step.

>> PIMA Diabetes Dataset is downloaded from the UCI portal & Header is added.

>> Checking correlation of all the 9 features by plotting against each other.

>> Splitting Features from Target 

>> Converting Data to array for computational needs such that the Gaussian - NB can be applied.

>> Gaussian NB gives the best acuracy on Normalized data.

>> Loading Libraries to apply Multinomial Naive-Bayes. 

>> Normalizing Data to create Parallel Coordinated plot, which unearths that the Higher values of Plasma_Glucose_Conc,Tristolic_Blood_Pressure & BMI leads to higgher chances of Diabetes.

>> Applying K-Nearest Neighbours algorithm to predict the acuracy, gives an accuracy which is lower than the Multinomial Naive-Bayes.

>> Also checking the data on Traditionaly used Logistic Regression used to make prediction in Binary Outcomes 0/1.

>> Logistic Regressin gives an Accuracy similar to Gaussian NB.

>> Exploring further results with altering the prediction probability & compairing results with new predictions.

>> Applying various techniques as GradientBoosting, Bagging, VotingClasssifer to get a better accuracy.

>> Final words of Conclusion.
