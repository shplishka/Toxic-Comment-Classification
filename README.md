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
      
      

> Toxic Comment Classification kaggle Score -> 69.29


