# BGreen

Application that allows you to log your activities, tracks how much CO2 you save and compares it to you friends.

![Image of statistics board](https://ibb.co/WzjpVwB)

## Installation instructions

##### Database setup:

1. Open the file `server/src/main/resources/application.properties`
2. Replace `{database}`, `{user}` and `{password}` with the name of the `database`, your PostgreSQL `user` and `password`

##### Commands for running the project:

1. Run the server <br>
    1.1 `cd server/` <br>
    1.2 `mvn spring-boot:run`
2. Run the client <br>
    1.1 `cd client/` <br>
    1.2 `mvn spring-boot:run`


`mvn clean install` -> Installs dependencies and executes unit tests

`mvn checkstyle:check` - Checks the code style for both client and server

To run any of the commands above for specific part (client or server), switch to the corresponding directory using `cd clien/t` or `cd server/` before executing the actual command

## Run tests

##### Tests ensure 70% branch coverage. Run them using this command:

1. 'mvn clean install'
