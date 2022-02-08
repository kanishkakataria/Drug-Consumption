# Drug-Consumption

<br>(Group project)</br>
This aim is to perform classification of a person as non-user or user of a certain drug given the personality traits (ethinicity,gender etc) and other records belonging to 7 classes of consumption for various drugs.
The 7 classes are segregated into two classes namely User and Non-user like "Never Used","Used over a decade Ago " forms a class a class of Non-user
<h3> Why This Dataset </h3>
<br>
Narcotic drugs or recreational drugs leave a devastating impact on the person who consumes it. Since, they result to chemical changes, parameters and properties of blood, can be used to predict the usage.
Drug use increases risk of poor health, along with earlier mortality and morbidity, and has significant consequences for society. 
Classification is done for this data to obtain valuable results which can be helpful in predicting and hence, eradicating drug usage.</br>
 

<h3> PREPROCESSING </h3>
<br>
<h2>1. ENCODING:</h2>
  </br>

<br>Encoding is a technique of converting categorical variables into numerical values so that it could be easily fitted to a machine learning model. In our project, one hot encoding is used.</br>

<br>One-Hot Encoding is a popular technique for treating categorical variables. It simply creates additional features based on the number of unique values in the categorical feature. Every unique value in the category will be added as a feature. </br>

<br>One-Hot Encoding is the process of creating dummy variables.</br>

<br>In some cases 2 Labels are derived, User and Non-user to show the final predictions as per grouping from the dataset.</br>

<br>Apart from this, not much preprocessing was required as the values were already quantified and normalised.</br>
<h3> ALGORITHMNS USED </h3>
<h2> KNN </h2>

<br>The KNN is a non-parametric, lazy-learning and  supervised learning algorithm that is based on principle that similar things exist in close proximity.</br>

<br>The steps for KNN approach are as follows:</br>

<br>1. Load the data. Initialize K to your chosen number of neighbors</br>

<br>2. For each example in the data,  Calculate the distance between the query example and the current example from the data.</br>

<br>3. Add the distance and the index of the example to an ordered collection and sort it in ascending order.</br>

<br>4. Pick the first K entries from the sorted collection. Get the labels of the selected K entries. /return the mode of the selected entries.</br>

<h2>2. DESICION TREE</h2>
<br>Decision Trees are a type of Supervised Machine Learning where the data is continuously split according to a certain parameter. The tree can be explained by two entities, namely decision nodes and leaves. The leaves are the decisions or the final outcomes. And the decision nodes are where the data is split.

In Decision Trees, for predicting a class label for a record we start from the root of the tree. We compare the values of the root attribute with the record’s attribute. On the basis of comparison, we follow the branch corresponding to that value and jump to the next node.</br>
  <br>In our project, Decision Tree classifier is used for binary classification: to classify a person as User or Non-user.
Attribute selection methods like information gain, Gini index etc. are used for deciding the root node and decision nodes. </br>

<h3> CONCLUSION </h3>
<br>
1.Binary classification (User / Non-User)  using Decision Tree on drugs that have high imbalance in the aforementioned 7 classes.</br>

<br>2. Multiclass classification ("Never Used", "Used over a Decade Ago" ,“Used in Last decade”, “Used in Last year”, “Used in Last Month, “Used in Last week”) using knn algorithm on the remaining drugs.</br>

<br>For both algorithms, hyperparameter tuning will be performed and results of various drugs will be compared. </br>
<br>The sought after metrics will majorly be precision and recall.</br>


  
