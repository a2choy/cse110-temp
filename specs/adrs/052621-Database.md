# Should we use a database for our Bullet Journal?

## Status
We've decided to use the IndexedDB API for our bullet journal since it is a local NoSQL efficient database.

## Context
We considered many options such as using usual cache storage, MongoDB etc. However, IndexedDB is a newer database with full functionalities of MongoDB (and equivalents) built into local web browswer. This makes IndexedDB the perfect fit for our purpose.

## Alternatives
Using local cache storage to preserve journal data.

## TA/Prof suggestions
Our TA was okay with us using any database and has allowed us to use any necessary tools to implement the database functionality in our bullet journal.

## Decision
Use 2 seperate IndexedDB databases for our to do list and journal entries.  

## Consequences
The format of our data will remain consistent (json).
We will have a NoSQL local database for our application.
We still have the option of switiching to cache storage incase of any failure.

