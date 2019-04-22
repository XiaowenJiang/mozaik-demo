# Mozaïk demo dashboards

[![Travis CI][travis-image]][travis-url]

This repository shows how to use Mozaïk with npm extensions, [installation instructions](http://mozaik.rocks/v1/use/).

## Configuration

> Two files are used to configure the dashboard content and layout

### .env

The project import dotenv, so that you can define environmental variables including HOST, PORT, etc.

An example .env file is put in this repo as a reference. [example file](./.env.example)

### config.js

This is the configuration file to configure the components and layout of the dashboard.
[config.js](./config.js)

## Set it up
There are several steps to follow to setup the dashboard on your server.

1. Clone this repository.
2. Run `sudo npm install` to install the dependencies.
3. Run `sudo npm run build-assets` to build the application.
4. Set variables in the .env file and modify the config.js as you need.
5. Run `node app.js` under the repository's root directory to start process.


[travis-image]: https://img.shields.io/travis/plouc/mozaik-demo.svg?style=flat-square
[travis-url]: https://travis-ci.org/plouc/mozaik-demo

