## Setting up environment variables:
- Set the MONGO_URI env-variable in the production environment
- PORT variable automatically set by the production environment

Steps to follow:
open CMD in the root folder of project and run:
npm install

to start the database server, run:
mongod

to create the new database, run (in a different CMD window):
use ms-engage

to start the server, run:
demon server.js 
or node server.ja

if no error, then go to browser at:
localhost:5000/
