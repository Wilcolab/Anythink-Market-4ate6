# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Assuming you're using WSL, do the following:

1️⃣ In your WSL2 environment, follow the [Linux install instructions](https://docs.docker.com/engine/install/ubuntu/).

2️⃣ Install [Docker Desktop for Windows](https://docs.docker.com/desktop/windows/wsl/). It'll prompt you to log out and login again, but after that, it should be properly installed.

3️⃣ Clone the repo to your machine, and inside the root directory, run `docker-compose up` to run the app. Go to http://localhost:3000/api/ping to test if everything is working properly!