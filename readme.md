# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Set up a local environment

In order to do this you first have to verify if docker is working by using the commands in your terminal: docker -v and docker-compose -v

Then you should check that you are in the project root directory.

Run docker-compose up

Now you test it by pointing your browser to http://localhost:3000/api/ping for the backend.

And to http://localhost:3000/api/ping for the frontend.
