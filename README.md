# Test NodeJS Server
Tests out a node js server that uses MongoDB to store a very simple task list.

## Prequisites
MongoDB must be installed prior to using this example.
Install MongoDB using the following instructions: https://docs.mongodb.com/manual/installation/

## Running the Service
First run MongoDB using: mongod --config /usr/local/etc/mongod.conf
Run npm server here: npm run start

## Testing the Service
Open Postman and run a GET to http://localhost:3000/tasks
Create a POST request with body x-www-form-unencoded with key: name, value: 'test task'
