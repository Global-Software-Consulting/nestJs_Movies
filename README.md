


![Nest](uploads/logo.png)
## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript repository that demonstrates the CURD of user and movies and all associate entities like, role base access JWT authentication.

### Technologies implemented:
-   [Nest](https://Nestjs.io/)
-   [PostgreSQL](https://www.postgresql.org/) + [sequelize-typescript](https://github.com/RobinBuschmann/sequelize-typescript) (ORM)
-   [JWT](https://jwt.io/)
-   [Swagger](https://swagger.io/)
-   [OAuth 2.0](https://oauth.net/2/)

## Prerequisites

-   [Node.js](https://nodejs.org/) (>= 14.14.36)
-   [npm](https://www.npmjs.com/) (>= 6.5.0)


## Key Feature
- Movie CRUD
- User Authentication
- User profile
- Social logins
- Author,Actor, geners and ProductionHouse CURDS
- rating and review of movies

## Code Structure
  we tried to implement the best practice of code structure in our project following are the example
  ```bash
  # all basic setup like database and constant that we need throughout application will fall in core folder
  - src/core/databse/*ts
  # middleware like file uploader will fall in middleware folder 
  - src/middlewares/*.ts
  # all the modules like user,movies  will fall in module folder uder there own folder 
  - src/modules/*/*.module.ts
  - src/modules/*/*.service.ts
  - src/modules/*/*.controllers.ts
  - src/modules/*/*.provider.ts
  # swagger documentation 
  - documentation/*
  # all java script files will build inthis distination folder
  - dist/*
  ```
## Environment Variables

The environment variables can be found and modified in the `.env` file. They come with these default values:

| env             |     DummyData      |
|---------------------|---------------|
| DB_HOST             | dbhost        |
| DB_PORT             | PORT          |
| DB_USER             | USER|
| DB_PASS             | PASS  |
| DB_DIALECT          | postgres      |
| DB_NAME_TEST        | dbName        |
| DB_NAME_DEVELOPMENT | dbName        |
| DB_NAME_PRODUCTION  | dbName        |
| JWTKEY              | JWTSecret        |
| TOKEN_EXPIRATION    | Time         |
| BEARER              | Bearer        |
| GOOGLE_SECRET       | GOOGLE_SECRET |
| CLIENT_ID           | CLIENT_ID     |
| APP_ID              | APP_ID        |
| APP_SECRET          | APP_SECRET    |


## How to Setup

#### Step 1: git clone this repo.

#### Step 2: cd to the cloned repo.

#### Step 4: Make sure you add the requires env in .env file check .env.example for help

#### Step 3: Install the npm modules required for the project with npm install


## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```



