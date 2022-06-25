# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** \_It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?

1. Clone the repo
    ```
    git clone https://github.com/ObelusFamily/Anythink-Market-5tuyp.git
    ```

2. [Install docker](https://docs.docker.com/get-docker/)

3. Verify docker is ready by running
    ```
    docker -v
    ```
    and
    ```
    docker-compose -v
    ```
    commands on your terminal.

4. Start docker desktop on your machine

5. Navigate to the project directory of the cloned repository and run,
    ```
    docker-compose up
    ```
