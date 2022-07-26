# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Mac
1. [Install docker and docker-compose](https://docs.docker.com/get-docker/)
    * verify installation by running `docker-compose -v` and `docker -v`
    * ensure that the docker desktop app is open
2. run `docker-compose up` in the project root
3. verify the site is up and running at http://localhost:3000/api/ping
4. create an account at http://localhost:3001/register
