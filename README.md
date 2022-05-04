## n8n with PostgreSQL

![images](https://user-images.githubusercontent.com/98898685/166658309-c8d63b14-578d-43b2-904d-c21aea6dc8a8.jpeg)


Starts n8n with PostgreSQL as database.

To start n8n with PostgreSQL simply start docker-compose by executing the following command in the current folder.

## IMPORTANT: But before you do that change the default users and passwords in the .env file!

docker-compose up -d
To stop it execute:

docker-compose stop

The default name of the database, user and password for PostgreSQL can be changed in the .env file in the current directory.
