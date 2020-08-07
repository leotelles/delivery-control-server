<h1 align="center">

Delivery Control

</h1>

<p align="center">A Node.js api for managing and controlling deliveries.</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
</p>

<hr />

## Features

- 📄 **JavaScript** — A programming language that allows you to implement complex things on web pages
- 💹 **Node Js** — A web framework for Node Js

## Getting started

1. Clone this repo using `git clone git@github.com:leotelles/delivery-control-server.git`
2. Move yourself to the appropriate directory: `cd delivery-control-server`<br />

3. We need to start the api. For that you'll need to:
-  Create a database in PostgreSQL and a redis container with docker.
-  Create a .env file following the format available on .env.example.
-  Run the following commands: 
```
yarn
yarn sequelize db:migrate
yarn sequelize db:seed:all
```
-  After that you can start the api with:
```
yarn dev
```
- And then, in a seperate command prompt:
```
yarn queue
```

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) page for details.
