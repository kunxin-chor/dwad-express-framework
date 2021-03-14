# Setting up NodeJS to work with MySQL

## Setting up the database

1. First, enter the `MySQL` client

   ```
   mysql -u root
   ```

2. Create the new database

   ```
   create database sakila;
   ```

3. Create the schema

   ```
   mysql -u root < sakila-schema.sql
   ```

4. Import the data

   ```
   import -u root < sakila-schema.sql
   ```
