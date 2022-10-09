# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. [Install Docker](https://docs.docker.com/get-docker/)
2. run docker
3. verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`
4. go to root directory 'Anythink-Market-2pafw'
5. run `docker-compose up`
6. go to `http://localhost:3000/api/ping` - if error on pending migration shows, click the `run pending migrations` button
8. create a new user at `http://localhost:3001/register`