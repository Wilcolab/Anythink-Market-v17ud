# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Clone the repo using command: 
```
git clone https://github.com/ObelusFamily/Anythink-Market-v17ud.git
```

From the root directory, run the following docker command:
```
docker-compose up
```
Verify the backend is running by going to:
```
http://localhost:3000/api/ping
```

You should see the following: 
msg: "Pong! Seems like Everythink is working, great job!

Verifh the frontend is running by going to:
```
http://localhost:3001/register
```
Once you verify the front end is running, create a new user account.

## Running commands on containters:
Use:
```
docker exec
```
