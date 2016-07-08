This folder contains all the mini-projects and assignments from the udacity course 
"introduction to machine learning" as well as some personal notes and cheat sheets I developed for myself.

## Projects

  * Naive Bayes
  
    - We have a set of emails, half of which were written by one person 
    and the other half by another person at the same company. 
    Our objective is to classify the emails as written by one person 
    or the other based only on the text of the email. 
    We will start with Naive Bayes in this mini-project, 
    and then expand in later projects to other algorithms.
    
  * SVM
  
    - We’ll tackle the exact same email author ID problem as the 
    Naive Bayes mini-project, but now with an SVM. 
    What we find will help clarify some of the practical differences 
    between the two algorithms. This project also gives us a chance 
    to play around with parameters a lot more than Naive Bayes did, 
    so we will do that too.
    
  * Decision-Trees
  
    - In this project, we will again try to identify the authors 
    in a body of emails, this time using a decision tree.
    
  * Regression
  
    - In this project, we will use regression to predict financial data 
    for Enron employees and associates. 
    
  * Outliers
  
    This project has two parts:
    
    - In the first part, we will run a regression, and identify and 
    remove the 10% of points that have the largest residual errors. 
    Then we’ll remove those outliers from the dataset and refit the regression.
    
    - In the second part, we will get acquainted with some of the outliers 
    in the Enron finance data, and learn if/how to remove them.
    
  * K-Means Clustering 
  
    - In this project, we’ll apply k-means clustering to our Enron financial data.
    since we have labeled data, this is not a question that particularly calls 
    for an unsupervised approach like k-means clustering. 
    Nonetheless, we’ll get some hands-on practice with k-means in this project, 
    and play around with feature scaling, which will give us a sneak preview of 
    the next lesson’s material.
    
  * Feature Scaling 
  
    - We’ll update the k-means clustering on the Enron characters using their 
    financial data as inputs from previous section to include scaled features, 
    to see how that changes things.
    
  * Text Learning 
  
    - In the beginning of this class, we identified emails by their authors 
    using a number of supervised classification algorithms. In those projects, 
    we handled the preprocessing, transforming the input emails into a TfIdf 
    so they could be fed into the algorithms. Now we will construct our own 
    version of that preprocessing step, so that we are going directly from 
    raw data to processed features. 
    
  * Feature Selection
  
    - In preparing Chris and Sara’s email for the author identification project, 
    there was a feature that was a little too powerful (effectively acting like a signature, 
    which gives an arguably unfair advantage to an algorithm). 
    We’ll work through that discovery process here.
    
  * PCA
  
    - In this mini-project we’ll play around with some sklearn code. The starter code can be 
    found in https://github.com/udacity/ud120-projects/blob/master/pca/eigenfaces.py
    The eigenfaces code is interesting and rich enough to serve as the testbed for this entire project.
  
  * Validation 
  
    - In this mini-project, we’ll start from scratch in making a training-testing split in the data. 
    This will be the first step toward the final project, of building a POI identifier.
    
  * Evaluation Metrics
  
  * Final Project
