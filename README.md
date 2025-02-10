# Personal-Finance-Tracker-Models
This project allows a user to track their income, expenses, and budget. It's simple enough to start with, but can be expanded to incorporate more complex features as you proceed....

# Level 1: Novice - Basic CRUD Operations & Data Modeling

## Goal: 
Implement basic Create, Read, Update, and Delete (CRUD) operations for income and expenses.

## MongoDB Concepts:

### Database and Collection Creation: 
Create a database (e.g., finance_tracker) and collections for users, income, and expenses.

### Basic Data Modeling: 
Define the schema for your documents. Consider these fields:

### Users: 
_id, username, password (hash it!), email

### Income: 
_id, user_id (reference to user), date, amount, source, category (e.g., salary, investment), description

### Expenses: 
_id, user_id, date, amount, category (e.g., food, rent, transportation), description

### insertOne(), insertMany(): 
Add sample income and expense data.

### find(): 
Retrieve all income or expenses for a specific user.

### findOne(): 
Retrieve a specific income or expense item by its _id.

### updateOne(): 
Update an existing income or expense item.

### deleteOne(): 
Delete an existing income or expense item.

### Basic Queries: 
Filter data using simple criteria (e.g., find expenses greater than $100).