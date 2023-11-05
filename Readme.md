# Overview

The aim of this project is to show how we can refactor an openapi spec for Rest API, so that we arrive at good (hopefully Restfull) solution.

# API

Api is located in `./api_spec` directory, it's supposed to cover the very basic flow of renting a book from library.

# Tools

Run `docker compose up`, to start the following services:
* `localhost:8080` - Prism
* `localhost:8081` - Swagger Editor
* `localhost:8082` - Swagger UI

Run `npm run openapi-generate`, to generate stub client/server code. Results will be saved to `./generated` directory. You can edit the configuration file `openapitools.json` to your needs, for that refer to [documentation](https://openapi-generator.tech/docs/generators/).