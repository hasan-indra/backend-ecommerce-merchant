# Backend API Ecommerce

## Description

This is a backend e-commerce project, part merchant using [Nest](https://github.com/nestjs/nest) framework. For database using postgresql (you can check ini docker-compose.yml.example)

## Feature

1. Product Managemang
2. JWT Auth

## How to install
```bash
# clone this project
$ git clone https://github.com/hasan-indra/backend-ecommerce-merchant.git

# run npm install
$ npm install

# copy docker-compose and run (if you using docker for database)
$ cp docker-compose.yml.example docker-compose.yml 
$ docker-compose up -d

# copy env and setup
$ cp .env.example .env

```

## License

[MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).
