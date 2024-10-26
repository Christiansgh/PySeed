# PySeed
A python-based tool for generating SQL dummy data.  
It creates a .sql file with a sql-command that inserts the data in the specified database.

## Usage
`$ pyseed <file> <flags>` 

## Flags
(defaults)
\* = required
\# = options

`-h`  help
`-d`\* the database type #sqlserver
`-t`\* the table name to insert into
`-s`  add *SELECT \* FROM table* statement
`-n`  name of the file (pyseed-script.sql)
`-p`  output path (current working directory)
