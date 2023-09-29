# Welcome to Airline Management Project
It consists of the following micro-services - 
1. FlightsAndSearch
2. BookingService

## FlightAndSearch
### Project Setup
- clone the project on your local
- execute `npm install` on FlightsAndSearch directory of the downloaded project.
- create a `.env` file in the root directory and add the floowing environment variable
  - `PORT = 3000`

- Inside `src/config` directory create a new file `config.json` and add the following json

```json
{
  "development": {
    "username": "<YOUR USERNAME>",
    "password": "<YOUR DB PASSWORD>",
    "database": "Flights_Search_DB_DEV",
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}
```
- execute `npx sequelize db:create` from FlightsAndSearch/src