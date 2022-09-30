# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Download and install Docker (https://docs.docker.com/get-docker/)and start the service on your machine - using the desktop app or through the command line. 

Once Docker has started (this can take a minute) cd into the project directory and enter the command: docker-compose up

This will take a few minutes while Docker sets up and starts a local development server. 

You can check the backend server is running by pointing you browser at the following url: http://localhost:3000/api/ping

Then, if all is well, head to: http://localhost:3001/register and create yourself a front-end login. 

That's it! You're ready to go!