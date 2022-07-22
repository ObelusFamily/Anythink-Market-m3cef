# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Install Docker (run **docker -v** and **docker-compose -v** in order to verify that Docker is running)
- Go to the root folder of your project in your terminal through cd-ing and run **docker-compose up**
- Verify that the backend is working properly by pointing your browser to http://localhost:3000/api/ping
- Verify that the frontend is working properly by pointing your browser to http://localhost:3001/register
