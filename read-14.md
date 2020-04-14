# Database Normalization
is a process used to organize a database into tables and columns.

## Reasons for Database Normalization:

1. to minimize duplicate data
2. to minimize or avoid data modification issues
3. to simplify queries.

##  Duplicated information presents two problems:

1. It increases storage and decrease performance.
2. It becomes more difficult to maintain data changes.

## Definition of Database Normalization

1. First Normal Form(1NF) : The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
2. Second Normal Form (2NF) :The table is in first normal form and all the columns depend on the table’s primary key.
3. Third Normal Form (3NF) :the table is in second normal form and all of its columns are not transitively dependent on the primary key

