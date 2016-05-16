# Mini-in-memorydatabase
Implemented reactive mini-in-memory database using Command, Memento and Observer design pattern
Used hashtable for NoSQL database, Strings as keys and Strings, Number, "Arrays" and "Objects" as data for hashtable.

Built database to support transactions and persistent using Memento design pattern.
Database is reactive by having the cursor which holds a value from the database. Cursor always holds the current state of the database. Any change in the database will be reflected in the cursor.
Implemented Observer pattern for Cursor, Command design pattern for database commands.

