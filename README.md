# Time-table
An automated Time-Table Generator.

## Concepts Covered
- MERN Stack
- Bootstrap
- Reactstrap
- Redux
- JWT Authentication

## Development and Installation
- Navingate to [time-table] folder and follow steps below:

### Install Backend Dependencies
- npm install

### Install Frontend Dependencies
- npm run client-install

### Setup up dev_keys for database
- Either run local MongoServer or,
- Setup Mongo Server at online platform like mlab and Create a keys_dev.js file in [config] folder and set up:-
``` 
module.exports = {
  mongoURI: YOUR_LOCAL_MONGO_SERVER_URI,
	secretOrKey: YOUR_SECRET
}; 
```
### Run
- npm run dev

## Note
The number of times we try to generate the final time-table is 20. After that it will show alert to try again. If you want to increase number of tries then change the value of "notPossibleCount < 20" from generator.js.

