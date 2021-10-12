# Predict-Future-Sales
Predict Future Sales using Simple Linear Regression, SVM, Decision Tree

This challenge serves as final project for the "How to win a data science competition" Coursera course.
Find the dataset from here: https://www.kaggle.com/c/competitive-data-science-predict-future-sales/overview

<h2>Data Description</h2>

You are provided with daily historical sales data. The task is to forecast the total amount of products sold in every shop for the test set. Note that the list of shops and products slightly changes every month. Creating a robust model that can handle such situations is part of the challenge.

<h2>File descriptions</h2>
<ul>
<li>sales_train.csv - the training set. Daily historical data from January 2013 to October 2015.</li> 
<li> test.csv - the test set. You need to forecast the sales for these shops and products for November 2015.</li> 
<li> sample_submission.csv - a sample submission file in the correct format.</li> 
<li> items.csv - supplemental information about the items/products.</li> 
<li> item_categories.csv  - supplemental information about the items categories.</li> 
<li> shops.csv- supplemental information about the shops.</li> 
</ul>

<h2>Data fields</h2>
<ul>
<li>ID - an Id that represents a (Shop, Item) tuple within the test set</li>
<li>shop_id - unique identifier of a shop
<li>item_id - unique identifier of a product
<li>item_category_id - unique identifier of item category
<li>item_cnt_day - number of products sold. You are predicting a monthly amount of this measure
<li>item_price - current price of an item
<li>date - date in format dd/mm/yyyy
<li>date_block_num - a consecutive month number, used for convenience. January 2013 is 0, February 2013 is 1,..., October 2015 is 33
<li>item_name - name of item
<li>shop_name - name of shop
<li>item_category_name - name of item category
 </ul>
