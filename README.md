🔗 Foreign Key (FK)

A Foreign Key is a field (or collection of fields) in a table that is used to create a link between two tables in a database.
It is a column that references the Primary Key of another table, ensuring that the relationship between both tables stays valid.

Foreign Key helps maintain referential integrity, meaning:
You cannot insert a value in the child table that doesn’t exist in the parent table.
You cannot delete a record from the parent table if it is being used in the child table (unless ON DELETE rules are applied).
It keeps the data consistent, connected, and reliable.

🔥 Why Foreign Keys Are Important?

Prevents invalid data from entering the database.
Connects tables in a relational database.
Helps in structured queries with JOIN.
Maintains real-world relationships (e.g., Customer → Orders).
 
