# Part 2

## Going once, twice...

You have been asked to get some answers from a database on a set of data. The database contains an archive of bids made by users for players over the years. The database contains years of data and you will need to write raw SQL queries to answer the questions.

Using the table structure below, provide the SQL queries required to answer as many of the following questions:

* What is the total number of users who have placed a bid on **Wayne Rooney** whilst playing for **Manchester United**?
* What is the total number of bids for **Cristiano Ronaldo** placed by users in Spain?
* What is the total number of users who have never placed a bid?
* What is the % of bids for each player
* What is the % of bids for each team
* Rank teams in order of the # of bids their players have had.

#### Bonus points

Optimisation is important at this scale – based on what you know already, are there any optimisations or things we should consider addressing?

#### The table structure

**Users**

| id | username | country |
|---|---------|-------|
| 1 | John Smith | UK |
| 2 | Samson Glen | US |
| ... |
| 20000000 | Antonio García | ES |
| 20000001 | Jane Lee | UK |

**Bids**

| id | user_id | player_id | value | date |
|---|------|-----|-----|----|
| 1 | 1 | 2 | 23.00 | 2015-08-23 00:00:12 |
| 2 | 1 | 3 | 5.25 | 2015-08-23 00:01:25 |
| ... |
| 4294967290 | 20000000 | 13946 | 15.25 | 2018-01-03 14:01:22 |
| 4294967291 | 19001032 | 939462 | 100.00 | 2018-01-03 14:01:23 |

**Players**

| id | name | team |
|---|-----|----|
| 1 | Henrik Larsson | Celtic |
| 2 | Wayne Rooney | Manchester United |
| ... |
| 4553945 | Wayne Rooney | Everton |
| 4553946 | Cristiano Ronaldo | Real Madrid |