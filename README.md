# Kaggle-projects
## TOXIC COMMENT CLASSIFICATION

> It is built in Python3 

###**ABOUT FILES**

>Toxic comment classification problem.py (main python file)

>submissions.csv (final submission file(using count vectorizer))

>submissions_tfidf.csv (final submission file(using tfidf vectorizer))

###**DATASET FILES(kaggle)**

>train.csv
 
>test.csv

>samplesubmissions.csv

###**DATA WRANGLING**

>Lowercasing all the comments

>Removing String Punctuation(eg- !,$,%)

>Removing new line character, return carriage character('\n','\r')

###**DATA ANALYSIS**

>Length of all training points

>Calculating mean, max , standard length of training dataset

>Ploting using library matplotlib

###**STATISTICAL MODEL**

 ####**Features Extraction**
 
       > Count Vectorizer- count the occurence of word in the comment(returns numpy array)
       
                                    **OR**
                                    
       > Tfidf Vectorizer- It return the frequency of that word(importance of that word)
       
 ####**MODEL USED**
 
      > One Vs Rest Classifier for multilabel classification problem which is using SGDC(Stochastic Gradient Descent Classifier)
      
      
## DOG BREED CLASSIFICATION

>It is bulit in python2 as graphlab supports in python2

###**ABOUT FILES**

>Dog Breed Classification.py (main python file)

>dog_breed_submissions.csv (final submission file)

###**DATASET FILES(kaggle)**

>train
 
>test

>labels.csv

>samplesubmissions.csv

###**DATA WRANGLING**

>Converting string labels into numerals

>Assigning labels to train data

>Using graphlab library for better image analysis

>Deep feature extraction for each image in our train data

###**DATA ANALYSIS**

>Checking the total number of labels

>Analyse the top most cateogry(i.e, frequent no. of dogs in the particular category)

###**STATISTICAL MODEL**

 ####**Features Extraction**
 
       > Deep feature extraction
       
 ####**MODEL USED**
 
      > k-nearest neighbour classifier for prediction of probability for each class or label.
         
### KAGGLE SUBMISSIONS

> [https://www.kaggle.com/ridhimagarg/kernels]

> Toxic Comment Classification kaggle Score -> 69.29

> Dog Breed Classification Kaggle Score -> 30.04
