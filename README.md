# E-Commerce Back End

[![owner Owner](https://img.shields.io/badge/Owner-Connerjm-green)](https://github.com/connerjm)
[![tech Tech](https://img.shields.io/badge/Tech-NodeJS-blue)](https://github.com/topics/node-js)
[![tech Tech](https://img.shields.io/badge/Tech-Sequelize-blue)](https://github.com/topics/sequelize)
[![tech Tech](https://img.shields.io/badge/Tech-Express-blue)](https://github.com/topics/express-js)
[![license License](https://img.shields.io/badge/License-Unlicense-orange)](https://www.opensource.org/licenses/unlicense)

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Usage](#usage)
- [Demonstration](#demonstration)
- [License](#license)

## Description

This application is a backend server for an e-commerce site. This is done utilizing express as the server base and sequelize to interact with the database, as well as dotenv to keep your environment variables safe. Since this is just a backend application, you may wish to utilize [Insomnia](https://insomnia.rest/) or a similar application to interact with it.

## Features

With this application, one is able to:

- Get categories, products and tags.
- Get single categories, products, or tags.
- Post, Put, and Delete categories, products, and tags.

## Usage

Install the application.

```Bash
git clone https://github.com/Connerjm/E-Commerce_Back_End.git
```

Install dependencies.

```Bash
npm i
```

---

**Remember to create the database using the schema file in the db folder locally before continuing.**

**Also, edit the .env file with your information.**

---

Seed the database if you require sample data.

```Bash
npm run seed
```

Then you may begin the server.

```Bash
npm start
```

## Demonstration

This demo will show how to create the schema, seed the database, begin the server as well as a few uses of the application itself.

![Demo](./assets/Demonstration.gif)

## License

E-Commerce Back End is released under the [Unlicense](https://www.opensource.org/licenses/unlicense).
