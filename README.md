# ASSIGNMENT-1
BASIC EXCEL FORMULAS
PERFORM THE FOLLOWING EXCEL FORMULA IN THE GIVEN DATASET WITH EQUATION
1) Sum, Count, Average:	
	• Total price of all products in the dataset = [=SUM(D2:D35)]
	• Number of products are there in the dataset = [=COUNTA(B2:B35)] Here we use 'COUNTA" function Because of PRODUCTS are in the text format.
	• The average price of the products =[ =AVERAGE(D2:D35)]
2) Min and Max:	
	• The minimum price among all products = [=MIN(D2:D35)]
  • The maximum price among all products = [=MAX(D2:D35)]
   
4) IF Function:	
	• Using an IF function, create a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.
                      * Create a new column and named as Price Range
                      * =IF(D2>=500,"High Price","Standard Price") [Using this Formula to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.
   
	
6) SUMIF and COUNTIF:	
	• The total price for products in the 'Electronics' category using the SUMIF function.
               * =SUMIF(F2:F35,"Electronics",D2:D35)
	• Count of products with a price less than $100 using the COUNTIF function
          * =COUNTIF(D2:D35,"<100")
	
8) Text Formatting - LEFT, RIGHT, MID:	
	• Create a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function.
                        *Created a column and named as 'Day'
                        * =LEFT(A2,2) [ using this formula to take the first 2 characters from left of 'Product ID'
	• Create a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function.
                        * Created a column and named as 'Country Code'
                        * =RIGHT(A2,2) [using this formula to take the last 2 character from right side of 'Product ID'.
	• Create a new column named Month by extracting 4th to 6th characters from the 'Product ID' column using the MID function.
                        *Created a column and named as 'Month'
                        * =MID(A2,4,3) [using this formula to take the mid character from "product ID" and also here 4 refers to the initial starting of character from the text and 3 refers to the how much character we want from the initial starting]
	





