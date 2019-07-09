# Twitter Classification Of Nepal Earthquake Tweets


# Introduction:<br>
This is a case study done Classification Of Nepal Earthquake Tweets.
### Data Fields Explanation
The Twitter Classification Of Nepal Earthquake Tweets dataset consists of 18226 Tweet Entries. This Dataset consists of a Text data (Train.txt)(We need to convert it first into csv data (Tweets.csv)). The columns in the table are:
<ol>
  <li>TweetClass: Class of Tweet Type(Irrelevant,Need,Availability)</li>
  <li>TweetId: Unique Id</li>
  <li>Tweet: Text data of Tweets</li>
 </ol>

# Dataset:
Dataset can be download from below given link-
https://drive.google.com/file/d/18c33mwHSkcukt5UiB9TMphCQBzyIokCI/view?usp=sharing/ 

The dataset is in the form of a txt file:
The text file contains tuples in the form:
(target class,Tweet id,Tweet’s text)


 #### Tweets given in the file are classified into following fields:<br>
<ol>
<li>0: The tweet doesn't talk about any resources needed or available (Irrelevant tweets)

<li>1: The tweet mentions a resource that is needed (Need Tweets)

<li>2: The tweet mentions a resource that is available (Availability tweets)
 </ol>
 
<h3><b>Following Models are trained on the given data</b></h3>
<ol>
    <li>LogisticRegression</li>
    <li>KNN (K Nearest Neighbor)</li>
    <li>SVM (Support Vector Machine) With Linear and RBF Kernel</li>
    <li>Naive Bayes</li>
    <li>Decision Tree</li>
    <li>Random Forest</li>
</ol>
