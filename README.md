 #SQL_Music_Store_Analysis (Interactive Dashboard creation using  Postgre SQL, PgAdmin4)
##Project Objective
The objective of this project is to explore and analyze data from a music store using SQL. It aims to find useful insights like best-selling tracks and customer preferences.

## Dataset used
-<a href="https://github.com/Sakshi-sharma2003/SQL_Music_Store_Analysis/blob/main/Music_Store_project.sql">Project</a>

## Questions (KPis)
/*	Question Set 1 - Easy */

- Q1: Who is the senior most employee based on job title? */
- Q2: Which countries have the most Invoices? */
- Q3: What are top 3 values of total invoice? */
- Q4: Which city has the best customers? We would like to throw a promotional Music Festival in the city we made the most money. 
      Write a query that returns one city that has the highest sum of invoice totals. 
      Return both the city name & sum of all invoice totals */
- Q5: Who is the best customer? The customer who has spent the most money will be declared the best customer. 
      Write a query that returns the person who has spent the most money.*/


/* Question Set 2 - Moderate */
- Q1: Write query to return the email, first name, last name, & Genre of all Rock Music listeners. 
Return your list ordered alphabetically by email starting with A. */
- Q2: Let's invite the artists who have written the most rock music in our dataset. 
Write a query that returns the Artist name and total track count of the top 10 rock bands. */
- Q3: Return all the track names that have a song length longer than the average song length. 
Return the Name and Milliseconds for each track. Order by the song length with the longest songs listed first. */

/* Question Set 3 - Advance */
- Q1: Find how much amount spent by each customer on artists? Write a query to return customer name, artist name and total spent */
- Q2: We want to find out the most popular music Genre for each country. We determine the most popular genre as the genre 
      with the highest amount of purchases. Write a query that returns each country along with the top Genre. For countries where 
      the maximum number of purchases is shared return all Genres. */
- Q3: Write a query that determines the customer that has spent the most on music for each country. 
      Write a query that returns the country along with the top customer and how much they spent. 
      For countries where the top amount spent is shared, provide all customers who spent this amount. */

## Process
-Understand the Data
 Look at the database tables (like customers, invoices, tracks, artists) and understand what each one contains.
-Set Project Goals
 Decide what you want to find out, like top-selling songs, best customers, or most popular genres.
-Write SQL Queries
 Use SQL to ask questions from the data, like “Which artist sold the most tracks?” or “Which customer spent the most money?”
-Analyze the Results
 Study the answers from your queries to find patterns or trends in sales, customer behavior, or music popularity.
-Make a Report
 Create a simple report or presentation to share what you found, using charts or tables to explain your results clearly.	

##Dashboard
![Uploading MusicDatabaseSchema.png…](https://github.com/Sakshi-sharma2003/SQL_Music_Store_Analysis/blob/main/MusicDatabaseSchema.png)

## Project Insight
-Top-Selling Genre
 Rock music is the most sold genre in the store.
-Best Customer
 One customer (e.g., from the USA) spent the most money on music purchases.
-Most Popular Artist
 A specific artist (e.g., AC/DC) has the highest number of track sales.
-Sales by Country
 The USA brings in the highest revenue, followed by countries like Canada and France.
-Monthly Sales Trend
 Sales are higher in certain months, showing a pattern that could help with planning promotions.

## Final Conclusion:
The analysis shows that Rock is the most popular music genre, and most sales come from the USA. A few top customers are responsible for a big part of the revenue. Artists like AC/DC have the highest track sales. These insights can help the store focus on popular genres, target high-value customers, and plan better marketing strategies based on sales trends.










