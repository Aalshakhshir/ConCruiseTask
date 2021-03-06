
## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start (localhost:3000)

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## cli usage:

after installation of all modules using yarn

List all customers/drivers npx nestjs-command customers OR npx nestjs-command drivers

for help npx nestjs-command
for exit npx nestjs-command exit

## Test

```bash
# unit tests
$ npm run test



## api testing examples

POST localhost:3000/customers (Add) 
dummy body {
    "name": "abood",
    "currentLocation": "amman",
    "numberOfRides": 122,
    "rating": "3"
}
GET localhost:3000/customers (get all)

GET localhost:3000/customers/1 (by id)

DELETE localhost:3000/customers/1 (delete one by id)
POST localhost:3000/customers (delete more than one by ids)
 body {
    ids: [1,2]
}

PUT localhost:3000/customers/1 (Update) 
dummy body {
    "name": "abood",
    "currentLocation": "amman",
    "numberOfRides": 122,
    "rating": "3"
}


## Swagger

swagger is running on /api prefix localhost:3000

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```


## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).
