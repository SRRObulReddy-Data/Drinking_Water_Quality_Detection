# Connecting Database, Table Creation, Storing data 
SQLite is the software used for connecting to a database. A database has been created 
which consists of two tables “qfacts” and “rfacts” where "q" and "r" stands for quality and river. 
Initially the rfacts table contains only 1 row of data.

### Rfacts Table 
CREATE TABLE rfacts
(
pid varchar(6) NOT NULL,
s1 char(8), s2 char(8), s3 char(8), s4 char(8), s5 char(8), s6 char(8), s7 char(8), s8 char(8), s9 char(8), s10 char(8), s11 char(8), s12 char(8)
);

A table named rfacts is created and is used to store attributes of river. The table 
consists of 14, except the first column all the remaining columns are of char data type of length 
8. First column is used to determine the sample number hence it is assigned with a constraint 
NOT NULL which means the field should not be left empty while entering the data.

Rfacts Table 
Rfacts Data Entry 
In the database a new row has been added to the rfacts table as the user has clicked on the store 
button at the bottom of the above window.
Updated Rfacts Table 
### Qfacts Table 
When the user clicks on second button in the user interface the below window is displayed 
which consists of 6 attributes excluding the sample number and data related to quality factors 
is to be entered in the window by the user. 
Qfactors 
CREATE TABLE qfacts
(
sid varchar(6) NOT NULL,
s1 char(6), s2 char(6), s3 char(6), s4 char(6), s5 char(6), s6 char(6)
);

A table named as qfacts is created and is used to store attributes of water. The table 
consists of 7, except the first column all the remaining columns are of char data type of length 
6. First column is used to determine the sample number hence it is assigned with a constraint 
NOT NULL which means the field should not be left empty while entering the data. The qfacts 
table contains only 2 rows of data.  

Qfacts_Table 

After entering the data user needs to click on the button at the bottom of the window with the 
name store in order to store the data in the database. 

Qfacts_Data_Entry

In the database a new row has been added to the qfacts table and now it consists of 3 rows. 

Updated_Qfacts


