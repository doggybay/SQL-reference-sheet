# SQL Reference Sheet
---
## Accessing Postresql CLI Windows
1. Launch command prompt or powershell
2. Type runpsql (This assumes you havde enviornemnt variables set to the correct path)
3. Designate database server location (default is localhost)
4. Designate database name (default postgres)
5. Designate port (default 5432)
6. Designate username (default postgres)
## How to create a database
1. Using psql CLI run:
```SQL
CREATE DATABASE db_name;
```
note that there is a semicolon and it is required for SQL commands

### Optional
1.\l will list all databases and can be used to confirm database was created
## How to create a table
## How to get everything from a single table
## How to get one thing from a single table with a "where" clause
## How to add something to a table
## How to edit something inside of a table
## How to remove something from a table