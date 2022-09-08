# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Prerequisite(s)

Docker is needed in order to run the application. Download and install Docker for your machine by visiting: https://docs.docker.com/get-docker/

Once Docker is installed, you can verify the installation was successful by running the either of the following commands in your terminal:

```sh
$ docker -v
$ docker-compose -v
```

### Getting Started

With Docker installed, you're ready to start the application. Simply run the following command in the root directory of this repo:

```sh
$ docker-compose up
```

After a few moments, you can test whether the Docker setup was successful by visiting the following URLs for the respective components of the application:

To test the backend, visit: http://localhost:3000/api/ping

To test the frontend, visit: http://localhost:3001/register
