# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## How to setup the environment
1. Clone this project : git clone https://github.com/ObelusFamily/Anythink-Market-e3hki.git
2. Install docker with this url: https://docs.docker.com/get-docker/
3. After installation, you can verify the installation on your terminal by running the following commands in your terminals: *docker -v* and *docker-compose -v*
4. In the root directory of the project, run docker-compose up. This is to load Anythink's backend and frontend.
5. You are almost done with the setup. Next is to confirm that everything is working fine. You can test this by pointing your browser to http://localhost:3000/api/ping, if everything is fine, you will get a json response on your browser.
6. To confirm the frontend is connected to the backend, you can create a user by pointing your browser to this url: http://localhost:3001/register
7. You are set-up already. To run scripts on one of the containers you use: *docker-compose* up and to run commands in a running container you can use *docker exec*


