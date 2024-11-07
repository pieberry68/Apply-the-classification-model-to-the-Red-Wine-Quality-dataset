# Apply-the-classification-model-to-the-Red-Wine-Quality-dataset
Apply classification models ( Logistic Regression, Naïve Bayes and Support Vector Machine ) to the data set related to the red variation of  Portuguese wine "Vinho Verde" (collectively called Red Wine Quality). Handle the problem of data imbalance and analyze how to classify labels so that the accuracy of the model is as high as possible.
- Input variable: 
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 – alcohol
- Output variable: 
12 - quality (from 0 to 10)
The data consists of 1599 samples and 12 columns.
- From label statistics, it is easy to see that there is a serious imbalance between labels (labels 5 and 6 have more than 600 samples but labels 4 and 8 have less than 100).
- There are 3 ways:
 Classify according to 6 labels and handle imbalance using oversampling method (SMOTE candidate)
 Classification by 2 binary labels 0 and 1 (almost balanced with label 0 (from 5 or less) accounting for 54% and label 1 (from 6 or more) accounting for 46%)
 Classified by 3 labels, Good, Average, Poor with the Average label being the majority (Nominated for Near Miss or CondensedNearestNeighbour)
