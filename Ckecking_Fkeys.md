#Scipts for Ckecking Foreign

### This Script write a statement to retrieve information
about tables and its constraints

>SELECT * FROM information_Schema.TABLE_CONSTRAINTS
WHERE information_schema.TABLE_CONSTRAINTS.CONSTRAINT_TYPE = 'FOREING KEY'
AND information.TABLE_CONSTRAINTS.TABLE_SCHEMA = 'dbCollege'
AND information_schema.TABLE_CONSTRAINTS.TABLE_NAME = 'Mytable';

