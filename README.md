# Paper-Review-Project

Steps to run the Paper Review Projects

Part 1
1. Clone this gitbug repository.initialized witha "source" command
2. FOLDER_PATH is where this project is downloaded IN YOUR SYSTEM followed by the .sql file name initialized witha "source" command.
3. Open MySQL command line client. 
4. Run the following command to setup the database
   mysql> source FOLDER_PATH\1_create_database.sql
5. Run the following command to create the database schema
   mysql> source FOLDER_PATH\2_create_database_schema.sql
6. Run the following command to insert data into the database
   mysql> source FOLDER_PATH\3_insert_database_values.sql
7. Run the following command to alter the database schema
   mysql> source FOLDER_PATH\4_alter_database_schema.sql
8. Run the following command to insert data into the paper table
   mysql> source FOLDER_PATH\5_update_database_values.sql
