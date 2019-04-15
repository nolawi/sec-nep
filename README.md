
## Table of Content


  * [Getting Started](#getting-started)
  * [Useful Commands](#useful-commands)
  * [Make It Your Own](#make-it-your-own)
  * [Goals](#goals)
  * [Learning Materials](#learning-materials)
  * [List of Projects Built Using This Starter](https://github.com/tomastrajan/angular-ngrx-material-starter/blob/master/BUILT_WITH.md)
  * [Features](#features)
  * [Stack](#stack)
  * [Code of Conduct](https://github.com/tomastrajan/angular-ngrx-material-starter/blob/master/CODE_OF_CONDUCT.md)
  * [Contributors Guide](https://github.com/tomastrajan/angular-ngrx-material-starter/blob/master/CONTRIBUTING.md)
  * [Changelog](https://github.com/tomastrajan/angular-ngrx-material-starter/blob/master/CHANGELOG.md) ( get notified about the newest releases, [follow Release Butler](https://twitter.com/releasebutler) on Twitter )


## Getting started
```bash
git clone https://github.com/tomastrajan/angular-ngrx-material-starter.git new-project
cd new-project
npm install
npm start
```

## Useful Commands
  * `npm start` - starts a dev server and opens browser with running app
  * `npm run test` - runs lint and tests
  * `npm run watch` - runs tests in watch mode
  * `npm run cy:open` - opens the Cypress Test Runner in interactive mode
  * `npm run cy:run` - runs Cypress tests via the cli
  * `npm run prod` - runs full prod build and serves prod bundle
  * `npm run prettier` - runs prettier to format whole code base (`.ts` and `.scss`) 
  * `npm run analyze` - runs full prod build and `webpack-bundle-analyzer` to visualize how much code is shipped (dependencies & application) 
  * `npm run compodoc` - runs [Compodoc](https://compodoc.app) to generate a static documentation of the application 

![analzye](https://raw.githubusercontent.com/tomastrajan/angular-ngrx-material-starter/master/meta-assets/analyze.png)
## Run Inside Docker Container
  * `docker build -t material-starter .` - builds docker image with name `material-starter`
  * `docker run -it \
   -v ${PWD}:/usr/src/app \
   -v /usr/src/app/node_modules \
   -p 4200:4200 \
   --rm \
   material-starter` - starts `material-starter` container (you can access running application browsing http://localhost:4200) 

#### Theming 

  * [Presentation (Slides)](http://slides.com/tomastrajan/angular-material-themes-guide#/)
  * [Live coding Video Tutorial](https://www.youtube.com/watch?v=PsgZjFTAleI)
  * [Meetup Presentation & Live coding Video](https://www.youtube.com/watch?v=7auj9RfCNrE)

 
## Features

* custom themes support (4 themes included)
* lazy-loading of feature modules
* lazy reducers
* localStorage ui state persistence
* `@ngrx/effects` for API requests
* fully responsive design
* angular-material and custom components in `SharedModule`
* Cypress for end to end tests
* `Production.Dockerfile` for quick and easy serving of your app
 
## Stack

* Angular
* ngrx (or try [ngx-model](https://github.com/tomastrajan/ngx-model) if you prefer less boilerplate)
* Angular Material
* Bootstrap 4 (only reset, utils and grids)

## Troubleshooting

* **Blocking at emitting LicenseWebpackPlugin when npm start** - try using [cnpm](https://github.com/cnpm/cnpm) instead of npm

## Contributors


Get started by checking out list of open [issues](/issues) and reading [Contributor Guide](.md)


