# German-eBay-dataset

This project was taken as an exercise to practice data cleansing. The dataset consists of vehicles classifieds section of the German eBay website for vehicles.
The question I wanted to ask the characteristics of the most popular brands on eBay. The data set was download from Kaggle https://www.kaggle.com/orgesleka/used-cars-database.
<br>
Steps:
**Import Packages,Read dataset,Explore data,Detecting missing values,Detecting anomalies,Imputing for missing values,Merging issues,Joining multiples datasets**
<br>
<br>
What I learned:
<br>
<br>
1-The method describes shows the number of unique values, but in some situations you can have no unique values, but it does not mean the values are the same.
e.g.: in a class with students from many countries such as Brazil, Argentina, Mexico, and Japan. If you use the method described in the unique value you can have null values, because you can have 2 from Argentina, 2 from Mexico and 2 from Japan. 
A more accurate way would be using the described method and for the columns that have null unique values, you applied the value_counts method because it separates in blocks using our example it would say we have 2 from Argentina, 2 from Mexico and 2 from Japan.
<br>
<br>
2-It is safer to create a list of columns you want to delete, instead delete one-by-one.
<br>
<br>
3- Sometimes you can fix missing values with values in other rows.In this project there missing values for the category of a car model, but you checking another row with the same model you can just find out the category. the procedure it explained in the project.

