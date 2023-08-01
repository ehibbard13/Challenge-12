# Challenge-12

Setup

For the setup jupyter notebook file I created a database and collection to be able to complete the rest of the assignment. 

I pretty printed the first document within the establishments collection and assigned a varible to the establishments collection. 

I then spent the rest of this jupyter notebook to import new data and add to it. 

Once Penang Flavours had been ammended I found how many documents have a 'Local Authority Name' of Dover and deleted them. I then checked to see what was remaining. 

I then changed some of the data values to be properly formatted into decimal and checked to make sure it worked.

The rating values were also changed and then I checked to make sure it would populate correctly. 

Analysis

For the beginning of the analyis I did the same as for the Setup. 

I then created a query to find all the establishments with a hygiene score of 20 and dcounted them, also printing the first one. 

Once that was completed I but that pulled data into a data frame and printed the first 10 rows. 

For question 2 I created a query to find establishments with London and the Local Authority Name with a rating value greater than 5, printed the count, the first document and made it into a data frame. 

for question 3 I used the data from penang flavours to find establishments near them that had a rating value equal to 5 and sorted that highest to lowest, printed the data and converted it to a data frame. 

for question 4 I created several queries to then add to a pipeline and aggregate. I then printed the count of data found and only printed the first 10 rows. After a converted the data to a DataFrame. 
