## Wellcome to Wallarock backend

This is a project to final course of The IX Bootcamp Web of Keepcoding.
This backend is made with Node js and its Express framework
For initialize this backend follow the next steps.

### Start your Mongo database

### How to start a local mongodb instance for development

```sh
./bin/mongod --dbpath ./data/db --directoryperdb
```

### Install

```sh
npm install
```

To download the modules the npm modules.

### Install database

```
npm init-db
```

Initialize the database with 8 products and 3 users.

### Usage

```sh
npm start
```

To start the application.

### Development start

```sh
npm run dev
```

For use in development mode.

## API Methods

### List of products

GET /api/products/by/:userId

### Latest products

GET /api/products/latest
{
"\_id": "605bb8c956b8e2618a314ff3",
"name": "Camiseta",
"description": "nuevo",
"category": "clothes",
"quantity": 1,
"price": 50,
"created": "2021-03-24T22:10:17.365Z",
"\_\_v": 0
}

### Related products

GET /api/products/related/:productId

### Categories products

GET /api/products/categories

### Categories products list

GET /api/products

### List of users

GET /api/users

{
"\_id": "605bb8c956b8e2618a314fed",
"name": "Pedro Sanchez",
"email": "Pedro@example.com",
"created": "2021-03-24T22:10:17.308Z"
},

### User by Id

GET /api/users/:userId

### Create

POST /api/users body: { name: 'aasd', email: 'aasd@aasd.es' pass:'1234'}

### Update, Delete user

PUT, DELETE /api/users/:userID

## Author

👤 **Erika, Fran, Alvaro**
