# Angular CLI Heroku Boilerplate
This README outlines how to quickly deploy your Angular CLI project to Heroku.

## Prerequisites
* [Git](http://git-scm.com/)
* [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)

## Installation
* `git clone https://github.com/frankMagoba/angular-cli-heroku-boilerplate.git <your-project-name>`
* `cd <your-project-name>`
* `npm install`

## Running
### Running locally
* `npm start`
* Visit your app at [http://localhost:8080](http://localhost:8080)

### Deploying to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

**OR**

* Install [Homebrew](https://brew.sh/)
* `brew install heroku`
* `heroku create <your-project-name>`
* `git push heroku master`
* `heroku open`

## Changes Made to Original Angular CLI code

* Added [`server.js`](https://github.com/frankMagoba/angular-cli-heroku-boilerplate/blob/master/server.js)
* Added `@angular/cli` to dev-dependencies in [`package.json`](https://github.com/frankMagoba/angular-cli-heroku-boilerplate/blob/master/package.json)
* Added `@angular/compiler-cli` to dev-dependencies in [`package.json`](https://github.com/frankMagoba/angular-cli-heroku-boilerplate/blob/master/package.json)
* Added `postinstall` script to [`package.json`](https://github.com/frankMagoba/angular-cli-heroku-boilerplate/blob/master/package.json) that builds app for production deployment
* Edited `start` script in [`package.json`](https://github.com/frankMagoba/angular-cli-heroku-boilerplate/blob/master/package.json) to launch run [`server.js`](https://github.com/frankMagoba/angular-cli-heroku-boilerplate/blob/master/server.js) instead of Angular CLI server

## Support
Like this boilerplate? Support my developments.

[![Support via PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HEA5HCZ83ZAFC&source=url)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HEA5HCZ83ZAFC&source=url)

Please star this repository to help it gain exposure.
