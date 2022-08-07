# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Env Setup
1. Navigate to the project root directory
2. docker-compose up

### Env Testing
1. http://localhost:3000/api/ping - Confirm this gives a successful response. This is the Python backend
2. http://localhost:3001/ - Should bring us to the front end. This is the react frontend
