# Dynamic Dashboard project

## How it will work

- Frontend app will run on port we specify later
- Backend app will run on port 9000.
- There will be administration - user can add graphs and types of data from database in real time into his own dashboard
- Make and option for user to delete his own specified graphs and data visualisation
- Frontend will have thread that will every minutre call for and api and show the current data (interval might be defined by user or hard-coded)

# Tech Stack

## Frontend

- Typescript (Components - React), Make an iterfaces properly
- TailwindCSS (pretty tables -\_-)
- Charts.js - for graphs
- We might use some state management lib like redux - will be solved in future

## Backend

- Express (for api) - libs : cors, mysql and so on....
- MYSQL Database - no procedures and other slow stuff

# TODOS

## Frontend

- Create visual tree of components and how they will interact
- Code components above
- Figure out user authentication
- Make this beautiful

## Backend

- Figure user authentication for backend API access
- Create routes that will dynamically read data
- Figure out how to show all tables in database
