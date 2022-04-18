# Should we use a database for our Bullet Journal?

## Status
We're currently trying to get MongoDB running for our Bullet Journal application. We're also keeping local storage as a backup/alternative option.

## Context
None of us have used any database softwares/tools before, but we are trying to learn a new NoSQL databse tool, MongoDB, to preserve our journal data on the cloud. However, incase MongDB does not work smoothly (or if we can't implement it fully), we'll be using local storage for the purpose.

## Alternatives
Using local storage to preserve journal data

## TA/Prof suggestions
Our TA was okay with us using MongoDB and has allowed us to use any necessary tools to implement the database functionality in our bullet journal.

## Decision
Use MongoDB to implement the databse. However, simultaneously, also make sure that we can switch to local storage if need (at any point in time).

## Consequences
The format of our data will remain consistent (json).
We won't need to rely on local storage for any data preserving or retreival and will be using the cloud.
We have the local storage option as a backup so we won't fail in case we are't able to implement MongoDB successfully.

