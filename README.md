# E-Commerce Back End

## Description

This repository contains back-end code necessaary for an e-commerce website. Using Express.js and Sequelize, the server interacts with a persistent MySQL database that contains a site's various products, the categories those products fall into, and specific tags attached to each product.

## Table of Contents

- [Installation](#installation)
- [Tests](#tests)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Demo](#demo)
- [Questions](#questions)

## Installation

Use the following command to install dependencies:

```
$ npm i
```

## Tests

Use the following command for tests:

```
$ npm run test
```

## Usage

First initialize the schema.sql in a MySQL shell, then seed in the provided data in the regular command line with the following commands:

```
mysql> SOURCE db/schema.sql;
```

```
$ node seeds/index.js
```

The following command initializes the server:

```
$ node server.js
```

After the local server is spun up, a user can use Insomnia Core or a similar API client to interact with the database and perform GET, POST, PUT, and DELETE requests for products, product categories, and product tags.

## Credits

The Node packages [Sequelize](https://www.npmjs.com/package/sequelize), [Dotenv](https://www.npmjs.com/package/dotenv), [MySQL2](https://www.npmjs.com/package/mysql2#using-prepared-statements), and [Express](https://www.npmjs.com/package/express) were installed for this application. Starter code was provided by Trilogy Education Services.

## License

This project is licensed under the MIT license.

## Demo

A walkthrough video for how to use this code can be viewed [here](https://youtu.be/9JgFOEDMzoY).

## Questions

If you have any questions about this repository, open an issue or contact me directly at liaobrien123@gmail.com. You can find more of my work at [liaobrien](https://github.com/liaobrien).
