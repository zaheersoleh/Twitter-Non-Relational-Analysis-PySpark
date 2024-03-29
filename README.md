# Tweet Non Relational Data Analysis with Spark

## Objectives
The objective of this assignment is to utilize Spark for processing and conducting basic analysis on non-relational data, employing both its DataFrame and SQL interfaces.

## Methodology
The methodology involves Python code, SQL queries, shell commands, and markdown cells. The notebook is entirely reproducible, based on an AWS EC2 instance provided through the provided AMI, ensuring that others can obtain the same results.

## Part 1 - Setup
Begin by setting up Spark and fetching the project data.

### About the Data
We will use JSON data from Twitter, specifically gathered during a game of the MLB World Series featuring the Los Angeles Dodgers and Houston Astros.

## Part 2 - Comparing DataFrames and Spark SQL

For the next three questions, we will look at operations using both DataFrames and SQL queries.

### Q2.1 - Which 6 languages are most commonly used in tweets? Verify your result by executing it with both the dataframe and with SQL.

### Q2.2 - Which 5 time zones are most common among users? Verify your result with both the dataframe and SQL.

### Q2.3 - How many tweets mention the Dodgers? How many mention the Astros? How many mention both?

## Part 3 - More complex queries

For this section, you may choose to use dataframe queries or SQL. 

### Q3.1 - Team mentions by location

In which users' locations are the Astros and the Dodgers being mentioned the most? Consider each team separately, one at a time. Discuss your findings.

### Q3.2 - Which Twitter users are being replied to the most?

### Q3.3 - Which 12 verified users have the most followers? Which 12 unverified users have the most followers?

### Q4 - Analyze common words in tweet text

**Observations:**
- No slogans or 'go':
    - Tweets mentioning 'Astros': 62,219
    - Tweets mentioning 'Dodgers': 34,363
- 'earnhistory' and 'go':
    - Both words mentioned with 'Astros' only: 1,506 tweets
    - Not mentioned with 'Dodgers'
- 'thisteam' and 'go':
    - Both words mentioned with 'Dodgers' only: 2,194 times
    - Not mentioned with 'Astros'
- Other instances of both 'earnhistory' and 'thisteam' mentions:
    - Astros: 'thisteam' mentioned 172 times, 'earnhistory' mentioned 99 times
    - Dodgers: 'earnhistory' mentioned, 'thisteam' not mentioned

