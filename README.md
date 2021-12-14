# EmplManagerBackEnd

Simple NodeJs backend service for retrieving employees by position.

## Setup

The project requires npm and nodeJs installed

### Build Project

1. Install typescrip: 'npm install -g typescript'
2. Install npx: 'npm install npx'
3. Install project dependencies: 'npm install'

## Lunch server

1. 'npx ts-node src/Server.ts'
2. Check localhost ap port [8080](http://localhost:8080/)

## Service:

| Position | Url |
|-----------|----| 
|All Employees | http://localhost:8080/allemployees|
|Juniors|http://localhost:8080/juniors|
|Programmers|http://localhost:8080/programmers|
|Engineers|http://localhost:8080/engineers|
|Experts|http://localhost:8080/experts|
|Managers|http://localhost:8080/managers|
|Admins|http://localhost:8080/admins|
|Nonadmins|http://localhost:8080/nonadmins|
