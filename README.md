# Salesperson
I have to confess it was a real challenge for me. It took me a couple of weeks to develop it. A lot of NullPointerException especially when adding a new entry in SalespersonDatabase.

The blueprint is simple. It has an ID and Sales Amount for one salesperson. The SalespersonDatabase gives 3 options; to add, delete or update an entry.

<strong>First</strong>: if the user selects the add option, it issues an error message if the database is full. Otherwise, it prompts the user for an ID number. if the ID number already exists in the database, it issues an error message. Otherwise, it prompts the user for a sales value, and add the new record to the database.

<strong>Second</strong>: if the user selects the delete option, it issues an error message if the database is empty. Otherwise, it prompts the user for an ID number. If the ID number does not exist, it issues an error message. Otherwise, it does not access the record for any future processing.

<strong>Third</strong>: if the user selects the change option, it issues an error message if the database is empty. Otherwise, it prompts the user for an ID number. If the requested record does not exit, it issues an error message. Otherwise, it prompts the user for a new sales value, and change the sales value for the record.

Extra: Though not asked, Exception handling was used in the exercise.

Extracted from the book:<br>
Java Programmingby Joyce Farrell, 7th Edition, 2014<br>
Salesperson.java - Exercise 6, page 437<br>
SalespersonDatabase.java - Exercise 5, page 492.
