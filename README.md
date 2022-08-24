# The Titanic Ship 1912: An Excel Capstone Project For 10Alytics Certificate 

As part of the requirement for obtaining my Mastering Data Analytics Certificate with 10Alytics and here is the details of my analysis. A case study of the Titanic Ship. 

# Data Sourcing 
https://drive.google.com/file/d/1CWV0jWjuOvynmzeHIllbVhAodK3iEPCU/view?usp=sharing

# Transformation

I duplicated the original sheet named as Titanic_raw. I noticed some formatting issues with the dataset: The name and Sex Column. There i created another table which contain which contained the names of the passengers. I nested the LEFT, RIGHT, LEN AND FIND function to divide the name columns into different column as FirstName and LastName and used flashfill function for the Title. 
I converted the data into tables and also formatted the Sex column since the attributes of the column is lowercase. I then joined all the firstName, Last Name and Title on another column FullName. 

There after I used INDEX-MATCH to match the Fullname in the Titanic_analzed spreedsheet from the passengers spreedsheet. Using this fuctions to create the Fullname and Sex column. 

There after I used IF function to create the age ranges, having used Measure of Tendency to fill in the missing records in the Age Column, precisely Age 30 as the mean as there are no outliers. Using this idea for the missing records in fare- Mean for fare 36$. Nesting IF and ISBLANK Function.

I transformed Q,S and C to Queenstown, Southampton and Cherbourg respectively using IF function.

Then I created my Calculation on another spreedsheet using pivottable




