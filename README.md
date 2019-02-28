# Store Manager

### Build Status

[![Build Status](https://travis-ci.com/jesseinit/store-manager-react.svg?branch=master)](https://travis-ci.com/jesseinit/store-manager-react)
[![Test Coverage](https://api.codeclimate.com/v1/badges/27e9c0000b8afbb10c08/test_coverage)](https://codeclimate.com/github/jesseinit/store-manager-react/test_coverage)

Store Manager is a web application that helps store owners manage sales and product inventory records.

## App Links

> [Store Maneger App](https://storemanagerly.herokuapp.com).

> [App Documentation](https://mystoremanager.herokuapp.com/docs).

## Implemented Features

- Admin can add a product
- Admin/store attendant can get all products
- Admin/store attendant can get a specific product
- Store attendant can add a sale order
- Admin can get all sale order records

## Extra Features

- Implement stock management functionality where attendants cant complete an order for an product that isn't available in the store.
- Store owner can give admin rights to a store attendant.
- Store admin/owner should be able to create categories an add product to that category.

## Project Management

Project is managed [here](https://www.pivotaltracker.com/n/projects/2204201) using the project management tool, [Pivotal Tracker](https://www.pivotaltracker.com).

## Templates

UI templates are hosted on Github pages [here](https://jesseinit.github.io/store-manager/ui/)

## Technologies Used

- [Node.js](https://nodejs.org) - A runtime environment based off of Chrome's V8 Engine for writing Javascript code on the server.
- [Express.js](https://expressjs.com) - Web framework based on Node.js.
- [PostgreSQL](https://www.postgresql.org) - An Object relational database.
- [Babel](https://babeljs.io) - Javascript transpiler.
- [Eslint](https://eslint.org/) - Javascript linter.
- [Airbnb](https://www.npmjs.com/package/eslint-config-airbnb) style [guide](https://github.com/airbnb/javascript) was followed.

### Testing tools

- [Mocha](https://mochajs.org/) - A Javascript test framework.
- [Chai](http://chaijs.com) - Assertion library.
- [nyc](https://github.com/istanbuljs/nyc) - Istanbul's command line interface.

## Getting Started

### Installation

- Install [NodeJs](https://nodejs.org/en/download/) and [PostgreSQL](https://www.postgresql.org/download/) on your computer.
- Create a database named `storemanager`
- Clone this repository using `git clone https://github.com/jesseinit/store-manager.git`.
- Run `npm install` to install all dependencies.
- Run `npm run migrations` to seed the database
- Run `npm run dev` to start the server.
- Navigate to [localhost:3000/api/v1](localhost:3000/api/v1) in your browser to access the application.

### Testing the application

Requirements

- [Postman](https://www.getpostman.com/) - API development and testing environment.

Testing with Postman

- Install Postman by following the link above.
- Navigate to `localhost:3000` in Postman to access the application.
- Use the API Documentation to access the endpoints available.

Running unit tests.

- In an open terminal, navigate to the cloned project file.
- Run `npm test`. This runs tests and displays coverage data generated by [Istanbul's](https://istanbul.js.org) nyc.

## Authors

- Egbosionu Obinna Jesse. 🤠
