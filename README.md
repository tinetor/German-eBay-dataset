# German-eBay-dataset
This project was taken as an exercise to practices the data analysis, the main focus was on data cleansing. The dataset consists of vehicles classifieds section of the German eBay website for vehicles.
What I learned:
The method describes show the number of unique values, It is not enough for deleting data because when you have Null unique values, it misleads you to think that the values are all the same. 
e.g.: in a class with students from many countries such as Brazil, Argentina, Mexico, and Japan. If you use the method described in the unique value you can have null values, because you can have 2 from Argentina, 2 from Mexico and 2 from Japan. 
A more accurate way would be using the described method and for the columns that have null unique values, you applied the value_counts method because it separates in blocks using our example it would say we have 2 from Argentina, 2 from Mexico and 2 from Japan.
