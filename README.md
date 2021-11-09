# Bookmark Manager Pairing Challenge :bookmark:
Task from Week 4 of the Makers bootcamp. This task was completed during daily pair-programming sessions with a new partner daily.

Day 1 partner --> [Will Sharkey](https://github.com/willjshark) - Challenges 1 to 4 completed. We paired using the driver-navigator technique to push-pull commits to our own machines as we took turns. 

## About the Task
This week's task has the purpose of developing our skills doing the following:
- Building a simple web app with a database (this primary goal breaks down into the two sub-goals below)
- Following an effective debugging process for database applications
- Be able to explain the basics of how databases work (e.g. tables, SQL, basic relationships)

## The project
You're going to build a bookmark manager. A bookmark manager is a website to maintain a collection of bookmarks (URLs). You can use it to save a webpage you found useful. You can add tags to the webpages you saved to find them later. You can browse bookmarks other users have added. You can comment on the bookmarks.

## Challenges
#### Challenge 1
- Generate User Stories from Requirements :white_check_mark:

```
As a user
To visit my favorite web pages easily
I would like to see a list of my bookmarks
```

##### Bookmark domain model

<img width="1229" alt="Screenshot 2021-11-09 at 10 42 17" src="https://user-images.githubusercontent.com/75947453/140900410-26f585d9-6191-4f89-a9bc-479a378e7d6c.png">


#### Challenge 2
- Set up a Ruby web project :white_check_mark:

#### Challenge 3
- Test driving development of a web application :white_check_mark:

#### Challenge 4
- Install PostgreSQL :white_check_mark:
- Create a database :white_check_mark:

#### Challenge 5
- Use the `psql` command to interact with Postgres :white_check_mark:
- Create tables using SQL :white_check_mark:

##### To set up the database

1) Connect to `psql` and create the `bookmark_manager` database:

```
CREATE DATABASE bookmark_manager;
```

To set up the appropriate tables, connect to the database in `psql` and run the SQL scripts in the `db/migrations` folder in the given order.

##### To run the Bookmark Manager app:

```
rackup -p 3000
```

To view bookmarks, navigate to `localhost:3000/bookmarks`.

##### To run tests:
run db/migrations/01_create_bookmarks_table.sql