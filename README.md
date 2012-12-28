# Moxboxx

## Installation instructions

Grab the [database file](https://dl.dropbox.com/u/1913694/moxboxx/moxboxx_prod_2012-12-08.sql) and create moxboxx_dev and moxboxx_test locally

Import the database file to set up the schema

Clone the repository

> git clone git://github.com/ednapiranha/moxboxx.git

> curl https://npmjs.org/install.sh | sh

Install node by using brew or through the website http://nodejs.org/#download

> cd moxboxx

> cp local.json-dist local.json

> npm install

Run the site

> node app.js

## Tests

> NODE_ENV=test make test
