# RAWG_API_Call
My first API call from https://rawg.io/


This project was more challenging but I gained some good experience in pulling data from a website and uploading this data into the cloud via AWS. 

I first had to pull data from the RAWG website and apply for an API key to have access to the data. 
Once I established access I pulled gaming data in the form of JSON files and populated a data frame with my desired columns. 

After some cleaning and transforming I set up Postgre RDS database on the AWS dashboard. 


I connected my code to the database with VS code and created a table that I would upload all my data to. 
Once the table was created I populated the database with my data frame in VS code.

<img width="984" alt="Screenshot 2023-02-08 at 15 58 41" src="https://user-images.githubusercontent.com/116017484/217801494-1adb85c8-1fcf-4d8e-a997-1c42962e8efe.png">
Example of database on the AWS dashboard

I then connected to the database with DBeaver which allowed me to write SQL commands to query the tabel in the cloud

<img width="545" alt="Screenshot 2023-02-08 at 16 00 04" src="https://user-images.githubusercontent.com/116017484/217801320-404b315c-19e6-4e8e-9b42-0e7a111ded10.png">
Example of a query in DBeaver

I also made some visuals of the data with plotly.express:

![ScatterPlot](https://user-images.githubusercontent.com/116017484/217800857-aad2af98-0343-426c-8cdc-e9fe313a2a49.png)
Here is a scatter plot showing the relationship between the games audience rating and metacritic score. 
I also fitted a regression line to highlight a possible linear relationship 


![HistPlot](https://user-images.githubusercontent.com/116017484/217800869-79b92b7c-6e59-4b6b-b54a-9d0cfdc4649d.png)
This histogram shows the distribution of the game ratings. 
