I have created the analysis on whats really the important deriving features of a quality wine . 
Dataset : 15000 data points consisting of 11 features and one target - quality ( 1- 10) . 
         most of the classes are 5,6,7  . there is a big difference of class imbalance. 

Preprocessing : balanced the class wigth the help of SMOTE . remapped the target variable by seperactig the lowest class from all the classes 
               Performed the standard scalinng of the data set 
               splitted the dataset into train and test with 80-20%

Training : After the use of many different models , finally used the randomforest with RandomisedsearchCV . 
Evaluation : got the weighted F1 score of 0.67 
