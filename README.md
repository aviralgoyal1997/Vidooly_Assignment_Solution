# Vidooly_Assignment_Solution
Tried to solve ad_org problem link : https://github.com/vidoolytech/hiringtask/tree/master/machine_learning/ad_org

<h3>File Information :</h3>
ad_org_solutin.ipynb :  Contains code performed for data cleaning,data transformation and exploratry analysis and ML models</br>
result_random_forest.csv : contains predictions made on ad_org_test data using random forest model</br>
result_xgb.csv : contains predictions made on ad_org_test data using random forest model</br>
ad_org_train.csv : data used for training.
ad_org_test.csv : data used for testing.

<h2>Steps performed in ad_org_solution.ipynb</h2> :<br>
  1.Data Cleaning : Removing missing values and faulty rows.<br>
  2.Data transformation : conversion of features publshed into days_passed till now and duration to duraion_seconds.<br>
  3.Exploratory Analysis : Insights gaied from visualiation .<br>
  4.Models : Random Forest with parameters tuning and xgboost.<br>
  <h3>Feature's Importance : </h3><br>
<img src="https://github.com/aviralgoyal1997/Vidooly_Assignment_Solution/blob/master/importance.png" alt="Features Importance"/>  
  
  
  <h2>Observations</h2><br>
1.What we conclude is C(maybe) and H(definately) category videos are ones with less ads compared to others.<br>
2.Categories with high standard deviation in views contains some of most viewed videos like category G.<br>
3.Category G contains videos with less no of ads as well as high no of ads.<br>
4.Category B and F videos gets more comments and likes compared to others.<br>
5.Catgory G which is most viewd category.<br>
6.Category D videos uploaded more than others.<br>
7.Category F videos most dislikes respective to their number of views.<br>
8.Category F with most number of comments respective to their number of views.<br>
9.Category F videos must be controversial as they are getting high likes,dislikes and also comments so maybe these are political videos.<br>
10.Comparative to total views category A got,most of ads showed in this.<br>
11.Category E contains some long videos compared to others.<br>
And many others possible to observe.<br>
