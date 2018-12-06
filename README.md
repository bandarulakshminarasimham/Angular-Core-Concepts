# Angular Core Concepts - created with basic knowledge...

This project shows several core features of Angular including:

* Components
* Data Binding
* Communication between components
* Services
* Routing

## Running the Project Locally

1. Install the Angular CLI

    `npm install -g @angular/cli`

1. Run `npm install` 

1. Run `ng serve -o`


## Running the Project Using Docker Containers

1. Install the Angular CLI

    `npm install -g @angular/cli`

1. Run `npm install`

1. Build the project

    `ng build`

1. Run `docker-compose build`

1. Run `docker-compose up`

1. Visit `http://localhost`

If you'd like to run the `production` version run `docker-compose -f docker-compose.prod.yml [build | up]`. This uses a multi-stage Docker build process to create the nginx image for the Angular app.
