# Sample Starter App

1. [Prerequisites](#prerequisites)
1. [Installation](#installation)
1. [Running](#running)

## Prerequisites

[Install MongoDB](INSTALL.md)

## Installation

```sh
npm install --global grunt-cli
npm install --global bower
npm install --global yarn
git clone git@github.com:caseconsulting/express-starter-app.git
cd express-starter-app
yarn install
bower install
```

create your initial user account

```sh
grunt execute
```

add to your .env file. [see the sample](env.example)

## Running

### Locally

```sh
grunt run:server
```
open a browser to http://localhost:3000/

### Production

```sh

```


