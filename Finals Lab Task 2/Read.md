## Finals Lab Task 2. Transforming ER Model to Relational Tables

Given the ER diagram representing student assignment submissions, convert it into MySQL tables. Capture all entities and their attributes, and define the relationships between students, submissions, and assignments. Identify the primary and foreign keys and ensure proper representation of any dependent or weak entities.

In converting the ER diagram, the following are the data types of the attributes:

## student table:
username: String (VARCHAR), up to 50 characters.

## assignment table:
shortname: String (VARCHAR), up to 50 characters.
due date: Date, cannot be null.
url: String (VARCHAR), up to 255 characters, can be null.

## submission table:
username: String (VARCHAR), up to 50 characters.
shortname: String (VARCHAR), up to 50 characters.
version: Integer, represents the version of the submission.
submit date: Date, cannot be null.
data: Text.
