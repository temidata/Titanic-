# The Titanic Ship 1912: An Excel Capstone Project

As part of the requirement for obtaining my Mastering Data Analytics Certificate with 10Alytics and here is the details of my analysis. A case study of the Titanic Ship. 

# Data Sourcing 
https://drive.google.com/file/d/1CWV0jWjuOvynmzeHIllbVhAodK3iEPCU/view?usp=sharing

# Transformation

I duplicated the original sheet named as Titanic_raw. I noticed some formatting issues with the dataset: The name and Sex Column. There i created another table which contain which contained the names of the passengers. I nested the LEFT, RIGHT, LEN AND FIND function to divide the name columns into different column as FirstName and LastName and used flashfill function for the Title. 
I converted the data into tables and also formatted the Sex column since the attributes of the column is lowercase. I then joined all the firstName, Last Name and Title on another column FullName. 

There after I used INDEX-MATCH to match the Fullname in the Titanic_analzed spreedsheet from the passengers spreedsheet. Using this fuctions to create the Fullname and Sex column. 

There after I used IF function to create the age ranges, having used Measure of Tendency to fill in the missing records in the Age Column, precisely Age 30 as the mean as there are no outliers. Using this idea for the missing records in fare- Mean for fare 36$. Nesting IF and ISBLANK Function.

I transformed Q,S and C to Queenstown, Southampton and Cherbourg respectively using IF function.

Next I created my Calculation on another spreedsheet using pivottable.

Having created the all my calculations with pivot tables, Then I used the piviot tables to create a dynamic Dashboard.


# Findings And Observation

1).Going with this dataset there where 418 Passengers that boarded the ship at which 266 (64%) of the passengers died 152 (36%) of the passengers survived.

2). All those who died where males and those who survived where females.

3). There were 218 (52%) passengers that boarded the ship with 3rd Class tickets, 107 (52%) passengers with second class tickets and 93 (23%) with third class ticket

4).The Youth Category were 275 (66%) passengers, Teenagers with 68 (16%) Passengers, Adults with 61 (15%) Passengers and the least category Elderly with 14 (3%) Passengers.

5). They were 52 passengers who had a child on the ship.

6). From my analysis on the dataset, they were 135 passengers whose siblings aboard the ship; of all the passengers who had siblings aboard the ship, 81% (110) of them had one (1) sibling aboard the ship. While 10% had two siblings, 3% covers both those who had 3 and 4 siblings respectively while the 2% for passengers who had 8 siblings and lastly 1% of passengers had 5 siblings on board.

7). The Total Fare Paid for the Journey is 14,892, Average fee paid is 36, Maximum 512 and Minumum 3.17. Although there are two passengers fee that didn’t pay but where on board in the ship.	

8). There are over three ports that was embarked: Queenstown, Cherbourg and Southampton. Over 270 (65%) passengers embarked on a Journey to Southampton Port while 102 (24%) passengers embarked to Cherbourg Port while the least port was port Queenstown with 46 (11%) passengers.

9). From my analysis, they were 50 females and 57 males who used the 1st class ticket, 30 females and 63 males who used the 2nd class ticket and finally, 72 females and 146 males used the 3rd class ticket.




