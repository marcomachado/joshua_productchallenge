# Product Challenge

## Installation instructions

### step 1

- Create the productchallengeservice database in Postgres (Flyway will create tables and first insert some data)
- Run the ProductChallengesServiceApplication class

### step 2

- Import the productchallengeservice project into your IDE of choice (I used STS)
- In the application.yml file, change the database credentials
- Run the ProductChallengesServiceApplication class

### step 3

- In the root of the productchallengefront project run: npm i -f
- Run the command: ng serve
- Access the url http://localhost:4200/
- Username = admin and Password = admin

### Using docker
 - Run the command: docker compose up
