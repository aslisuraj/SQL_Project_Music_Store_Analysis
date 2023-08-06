Project: Music Store Database

Objective: Design and implement a SQL database for a music store, allowing users to manage artists, albums, tracks, and customer orders.

Database Schema:

Artists

artist_id (Primary Key)
artist_name
genre
Albums

album_id (Primary Key)
album_title
artist_id (Foreign Key referencing Artists)
release_year
Tracks

track_id (Primary Key)
track_title
album_id (Foreign Key referencing Albums)
duration
price
Customers

customer_id (Primary Key)
first_name
last_name
email
phone
Orders

order_id (Primary Key)
customer_id (Foreign Key referencing Customers)
order_date
Order_Details

order_detail_id (Primary Key)
order_id (Foreign Key referencing Orders)
track_id (Foreign Key referencing Tracks)
quantity
Queries:

Question Set 1 - Easy:

Who is the senior most employee based on job title?
Which countries have the most Invoices?
What are the top 3 values of total invoice?
Which city has the best customers?
Who is the best customer?
Question Set 2 - Moderate:

Return the email, first name, last name, & Genre of all Rock Music listeners.
Find the top 10 rock bands and their total track count.
Return track names with a song length longer than the average song length.
Question Set 3 - Advanced:

Find how much amount spent by each customer on artists.
Determine the most popular music genre for each country.
Find the customer that has spent the most on music for each country.
Conclusion:
Now, let's add a fun and random aspect to your project's conclusion. You can generate a random recommendation for a track to a customer based on their past orders and preferred genre. Here's a simplified SQL query to achieve this:
