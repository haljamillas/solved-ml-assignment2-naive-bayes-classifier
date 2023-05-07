Download Link: https://assignmentchef.com/product/solved-ml-assignment2-naive-bayes-classifier
<br>
<strong>The following has to be done using Bayesian learning (Naïve Bayes classifier):</strong>

1) Randomly divide the data into 80% for training and 20% for testing. Apply the following:

<ol>

 <li>Handle the missing values in both train and test set. [5]</li>

 <li>Encode categorical variables using appropriate encoding method (in-built function allowed). [5]</li>

 <li>After completing step (a) and (b), compute 5-fold cross validation on the training set (normalisation of data is allowed, if required). Print the final test accuracy. [10]</li>

</ol>

2) Apply PCA (select number of components by preserving 95% of total variance) on the processed data from step (1).

<ol>

 <li>Plot the graph for PCA (in-built function allowed for PCA and visualisation). [20]</li>

 <li>Use the features extracted from PCA to train your model. Compute 5-fold cross validation on the training set (normalisation of data is allowed, if required). Print the final test accuracy. [10]</li>

</ol>

3) Using the processed data from step (1), apply the following:

<ol>

 <li>A feature value is considered as an outlier if its value is greater than mean + 3 x standard deviation. A sample having maximum such outlier features must be dropped. [5]</li>

 <li>Using the sequential backward selection method, remove features. [15]</li>

 <li>Print the final set of features formed. [5]</li>

 <li>Compute 5-fold cross validation on the training set (normalisation of data is allowed if required). Print the final test accuracy. [5]</li>

</ol>

4) Report and results. [20]

<strong>Dataset Description:</strong>

Use Train_F.csv as data for this assignment. The “severity_county_5-day” column will be used as labels.