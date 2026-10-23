# Mini-Project-1
Data Cleaning using excel
# Data Cleaning using excel

1.	Check and handle missing values

There is no missing values in this dataset. 

**Home → Find & Select** 

**=COUNTBLANK(C2:C5001)**

2.	Identify and remove duplicate records
 
There is no duplicate values. 

**Data → Remove Duplicates** 

3.	Standardize text values

Removed unwanted spaces and standardize text formatting in columns such as Customer Name, City, Category, and Payment Mode in power query. 

4.	Checked and correct date formats
   
6.	Created a sales category 

**= IF([Sales] >= 100000 then "High" else if [Sales] >= 50000 then "Medium" else "Low")**
