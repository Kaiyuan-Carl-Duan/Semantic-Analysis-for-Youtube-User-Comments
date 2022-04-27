# Semantic-Analysis-for-Youtube-User-Comments

## Write a Spark program to analyze the text data.

In this notebook, we have a dataset of user comments for youtube videos related to animals or pets. We will attempt to identify cat or dog owners 
based on these comments, find out the topics important to them, and then identify video creators with the most viewers that are cat or dog owners.

The dataset provided for this coding test are comments for videos related to animals and/or pets. The dataset is 240MB compressed; please download the file using this google drive link:
https://drive.google.com/file/d/1o3DsS3jN_t2Mw3TsV0i7ySRmh9kyYi1a/view?usp=sharing

 The dataset file is comma separated, with a header line defining the field names, listed here:  
● creator_name: name of the YouTube channel creator.  
● userid: integer identifier for the users commenting on the YouTube channels.  
● comment: text of the comments made by the users.  

## Steps:  

Step 1: Identify Cat And Dog Owners
Find the users who are cat and/or dog owners.

Step 2: Process Users Comments via RegexTokenizer and Word2Vec

Step 3: Build and Evaluate Classifiers (Logistic Regression & Random Forest)  
Build classifiers for the cat and dog owners and measure the performance of the classifiers.

Step 4: Extract Insights about Cat And Dog Owners  
Find topics important to cat and dog owners.
