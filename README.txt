CS 6360.5U1 - Database Design - Su18
Programming Project #2: Database Files and Indexing
Instructor: Chris Irwin Davis
Due: August 1, 2018 11:59PM

Team Orange members: Ujjawal Mishra, Pallavi Sinha, Usuma Thet, Vijay Venugopal

System Requirements:
Java Runtime Version - jre1.8.0_172

Steps to run through Command Prompt:
1) Extract the file and find the davisql jar file in db2sql-master\db2sql-master\davisql.jar
2) Open cmd prompt
3) Run the jar file using java -jar davisql.jar
4) Start entering the commands in the console. (Every command should be terminated by semicolon ;)

Steps to run through the IDE:
1)Please run DavisBasePrompt.java(src folder-default package). It will display the following into the console:
--------------------------------------------------------------------------------
Welcome to DavisBaseLite
DavisBaseLite Version v1.0
©2018 Orange Team

Type 'help;' to display supported commands.
--------------------------------------------------------------------------------
davisql>help;
********************************************************************************
SUPPORTED COMMANDS
All commands below are case insensitive

        USE DATABASE database_name;                      Changes current database.
        CREATE DATABASE database_name;                   Creates an empty database.
        SHOW DATABASES;                                  Displays all databases.
        DROP DATABASE database_name;                     Deletes a database.
        SHOW TABLES;                                     Displays all tables in current database.
        DESC table_name;                                 Displays table schema.
        CREATE TABLE table_name (                        Creates a table in current database.
                <column_name> <datatype> [PRIMARY KEY | NOT NULL]
                ...);
        DROP TABLE table_name;                           Deletes a table data and its schema.
        SELECT <column_list> FROM table_name             Display records whose rowid is <id>.
                [WHERE rowid = <value>];
        INSERT INTO TABLE [(<column1>, ...)] table_name  Inserts a record into the table
                VALUES (<value1>, <value2>, ...);      
        DELETE FROM TABLE table_name [WHERE condition];  Deletes a record from a table.
        UPDATE table_name SET <conditions>               Updates a record from a table.
                [WHERE condition];
        VERSION;                                         Display current database engine version.
        HELP;                                            Displays help information
        EXIT;                                            Exits the program


********************************************************************************

Please interact with the console then like a command line shell. 
All commands are case insensitive and those supported may be viewed by inputting the help; command. 
The database state will remain even after closing the workspace. 
