

Test your knowledge on SQL
==========================

Practice Quiz. • 10 min. • 5 total points available.5 total points

*   English

Assessment passed

Congratulations! You passed!
----------------------------

Grade received 100%




### 1.Question 1

![Screenshot of sql query](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/KvkiE7a5QLm5IhO2uYC5HQ_14edd03cdce04319852936eee8d5eb86_SQL1.png?expiry=1697414400000&hmac=e1A2iHWYsLTtFbEIsgDIf3BA-MyzlmAwMbk3GzRVeRA)

SELECT \* FROM employee WHERE jobCode = 'FTE' AND LastName = 'James'

## What does the asterisk (\*) after SELECT tell the database to do in this query?

1 / 1 point

* Select all data that meets the criteria as stated in the query, then multiply it
* [ **Select all columns from the employee table** ] 
* Select the LastName column from the employee table
* Select all data that meets the criteria as stated in the query

> Correct
> 
> SELECT \* tells the database to select all columns from the employee table. The criteria in the WHERE clause tells the database what data in those columns the query should return.

### 2.Question 2

![SELECT * FROM employee WHERE jobCode = 'FTE'  AND LastName = 'James'](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/MPKNh1iLTReyjYdYi70X6A_34a20684dcf244c993097bed830a5aa9_JXIL_POLTL6yC_zzixy-tw_b46c73cd95b444d1bd032569247b8c00_Untitled-8.png?expiry=1697414400000&hmac=lnEJPpbdQxj4cc5dgScr_7TN_aSXhmifzicF_3lKySw)

SELECT \* FROM employee WHERE jobCode = 'FTE' AND LastName = 'James'

## In this query, the data analyst wants to retrieve data from which table?

1 / 1 point

* jobCode
* LastName
* James
* [ **employee** ]

> Correct
> 
> The data analyst wants to retrieve data from the employee table.

### 3.Question 3

![SELECT * FROM employee WHERE jobCode = 'FTE'  AND LastName = 'James'](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/MPKNh1iLTReyjYdYi70X6A_34a20684dcf244c993097bed830a5aa9_JXIL_POLTL6yC_zzixy-tw_b46c73cd95b444d1bd032569247b8c00_Untitled-8.png?expiry=1697414400000&hmac=lnEJPpbdQxj4cc5dgScr_7TN_aSXhmifzicF_3lKySw)

SELECT \* FROM employee WHERE jobCode = 'FTE' AND LastName = 'James'

## In this query, what will be retrieved from the database?

1 / 1 point

* All data from the employee table, where the jobCode is FTE and the employee has any last name other than James.
* All data from the jobCode table, where the jobCode is FTE and the employee has any last name other than James.
* [ **All data from the employee table, where the jobCode is FTE and the last name is James.** ]
* All data from the FTE table, where the employee's LastName is James.

> Correct
> 
> This query will select all data from the employee table, where the jobCode is FTE and the last name is James.

### 4.Question 4

 You are working with a database table that contains data about music artists. The table is named _artist_. You want to review all the columns in the table. 

You write the SQL query below. Add a FROM clause that will retrieve the data from the _artist_ table.

> 
> SQL:  SELECT \* FROM artist
> 

## How many columns are in the _artist_ table? 

1 / 1 point

* 5
* 8
* 9
* [ **2** ]

> Correct
> 
> The clause FROM artist will retrieve the data from the _artist_ table. The complete query is SELECT \* FROM artist. The FROM clause specifies which database table to select data from. There are two columns in the _artist_ table.

### 5.Question 5

You are working with a database table that contains data about music albums. You are only interested in data related to the album with ID number 277. The album IDs are listed in the _album\_id_ column from the _album_ table.

You write the SQL query below. Add a WHERE clause that will return only data about the album with ID number 277.

> 
> SQL: 
> SELECT \*  FROM album
> WHERE album\_id \=277
> 


## What is the name of the album with ID number 277?

1 / 1 point

* [ **Bach: Goldberg Variations** ]
* Vivaldi: The Four Seasons
* Beethoven: Piano Sonatas 
* Mozart: Chamber Music

> Correct
> 
>The clause WHERE album\_id = 277 will return only data about the album with ID number 277. The complete query is SELECT \* FROM album WHERE album\_id = 277. The WHERE clause filters results that meet certain conditions. The WHERE clause includes the name of the column, an equals sign, and the value(s) in the column to include. The name of the album with ID number 277 is Bach: Goldberg Variations.
