# Yammer data exploration and analysis

The data used for the project are from tutorial.yammer_users and tutorial.yammer_events tables from Mode Public Warehouse.
The goal of the project is to identify the nature of data and find the reason for reduced user engagement over time. 

## Step 1

### Understanding nature of data.

Since the tables have only few columns each, a mind map was used to visualize the properties of data. Which includes:
* Table name
* Column name
* Data Type
* Minimum value
* Maximum valie
* Count
* Nullability
* Uniqueness
* Number of unique options 

Most of the information was captured using simple SQL queries. 
Improvement notes: Most queries were repetitive. A method to create a data dictionary from tables would be useful.

## Step 2

### Understanding the relationship between the tables and data rows

tutorial.yammer_users (users) contains a list of users created from January, 2013 to August, 2014

tutorial.yammer_events (events) contains a list of events that occurred from May, 2014 to August, 2014

Events have two types, Signup_flow and engagement. 

* What are events really? Events in this contects are user actions. 

After a user follows through the signup-flow, the user is activated and any action the user performs on the platform are engagement events.

* Why the time duration difference in the two tables? The focus during data extraction must be on events that occured between May to August, 2014.






