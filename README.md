


![Nest](uploads/logo.png)
## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript repository that demonstrates the CURD of user and movies and all associate entities like, role base access JWT authentication.

### Technologies implemented:
-   [sequelize-typescript](https://github.com/RobinBuschmann/sequelize-typescript) (ORM) + [PostgreSQL](https://www.postgresql.org/)
-   [JWT](https://jwt.io/)
-   [Jest](https://jestjs.io/)
-   [Swagger](https://swagger.io/)

## Prerequisites

-   [Node.js](https://nodejs.org/) (>= 14.14.36)
-   [npm](https://www.npmjs.com/) (>= 6.5.0)


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

## Environment Variables

The environment variables can be found and modified in the `.env` file. They come with these default values:

| evv              |     DummyData      |
|---------------------|---------------|
| DB_HOST             | dbhost        |
| DB_PORT             | 5432          |
| DB_USER             | postgres      |
| DB_PASS             | postgres      |
| DB_DIALECT          | postgres      |
| DB_NAME_TEST        | dbName        |
| DB_NAME_DEVELOPMENT | dbName        |
| DB_NAME_PRODUCTION  | dbName        |
| JWTKEY              | JWTKEY        |
| TOKEN_EXPIRATION    | 12h           |
| BEARER              | Bearer        |
| NODE_ENV            | DEVELOPMENT   |
| GOOGLE_SECRET       | GOOGLE_SECRET |
| CLIENT_ID           | CLIENT_ID     |
| APP_ID              | APP_ID        |
| APP_SECRET          | APP_SECRET    |


## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).




## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).
