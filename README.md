# Music Store Data Analysis using SQL

## About the Project

Music is something people enjoy every day, but have you ever wondered what the sales data of an online music store can tell us?

In this project, we worked with a music store database and used SQL to explore its data, understand customer behaviour, and find useful business insights.

The main idea was to practise SQL using a real-world style dataset rather than just writing queries on small sample tables. We explored different tables, connected related data using joins, and answered business questions using SQL queries.

## What We Wanted to Find

Through this project, we tried to answer questions such as:

- Who is the senior-most employee in the company?
- Which countries generate the most invoices?
- Which city brings in the highest revenue?
- Who are the customers spending the most money?
- Which music genres are the most popular?
- Which artists and tracks are purchased the most?
- Which songs are longer than the average track duration?
- How much do customers spend on different artists?
- Which genre is most popular in each country?

These questions helped us understand how SQL can be used to turn raw data into meaningful information.

## Tools and Technologies

- **PostgreSQL** – Used to store and query the database.
- **pgAdmin 4** – Used to connect to PostgreSQL, manage the database, and execute SQL queries.
- **SQL** – Used for data analysis and retrieving insights.
- **CSV Files** – Provided the original dataset used in the project.

## Database Overview

The database contains information about different parts of the music store, including:

| Table | Information |
|---|---|
| `employee` | Employee details and reporting structure |
| `customer` | Customer information |
| `invoice` | Customer invoice details |
| `invoice_line` | Individual items in each invoice |
| `track` | Music track details |
| `album` | Album information |
| `artist` | Artist details |
| `genre` | Music genres |
| `media_type` | Available media formats |
| `playlist` | Playlist information |
| `playlist_track` | Tracks associated with playlists |

These tables are connected through relationships, which allowed us to combine information and perform more detailed analysis.

## SQL Concepts We Practised

While working on this project, we used several SQL concepts:

- SELECT, WHERE and ORDER BY
- GROUP BY and HAVING
- Aggregate functions such as COUNT, SUM and AVG
- INNER JOIN and other joins
- Subqueries
- Common Table Expressions (CTEs)
- Window functions
- Sorting and filtering data
- Data analysis using multiple related tables

## Getting Started

To explore this project on your system, you will need:

1. PostgreSQL
2. pgAdmin 4 (or the PostgreSQL command-line tool)

### Step 1: Create a Database

Open pgAdmin and connect to your PostgreSQL server.

Create a new database named:

```sql
CREATE DATABASE music_store;
```

### Step 2: Restore the Database Backup

The repository includes a database backup file named `music_store_db_backup`.

You can restore it into the `music_store` database using pgAdmin:

1. Right-click the `music_store` database.
2. Select **Restore**.
3. Choose the `music_store_db_backup` file.
4. Select the appropriate backup format if required.
5. Start the restore process.

Once the restore is complete, the tables and their data will be available in the database.

### Step 3: Run the SQL Queries

Open the Query Tool in pgAdmin, open `analysis.sql`, and execute the queries.

You can also explore individual queries in `music_store_db_query.txt`.

## Project Files

```text
music_system/
│
├── analysis.sql
├── music_store_db_backup
├── music_store_db_query.txt
├── MusicDatabaseSchema.png
│
├── dataset/
│   ├── album.csv
│   ├── artist.csv
│   ├── customer.csv
│   ├── employee.csv
│   ├── genre.csv
│   ├── invoice.csv
│   ├── invoice_line.csv
│   ├── media_type.csv
│   ├── playlist.csv
│   ├── playlist_track.csv
│   └── track.csv
│
└── README.md
```

## What We Learned

This project gave us practical experience working with a relational database and writing SQL queries to solve business-related questions.

We understood how multiple tables are connected, how to retrieve information from them, and how SQL can help identify patterns in customer purchases and music preferences.

More importantly, it helped us become more comfortable with writing queries and applying SQL concepts to a practical dataset.

## Conclusion

The Music Store Analysis project was a useful hands-on exercise in SQL and database management. It helped us understand how data stored across multiple tables can be analysed to answer real business questions.

We will continue improving this project as we learn more about SQL and data analytics.

---

**Created by:** [Darshan A M](https://github.com/Darshan262005)

**GitHub Repository:** [music_system](https://github.com/Darshan262005/music_system)