# Webpack 4 boilerplate

## Requirements

You need [Node.js](https://nodejs.org/en/) installed on your system

## Install

You could download the boilerplate in your current directory with:

```sh
curl -L -o master.zip https://github.com/guar47/webpack-boilerplate/archive/master.zip && unzip master.zip && rm master.zip && mv -n ./webpack-boilerplate-master/{.,}* ./ && rm -r ./webpack-boilerplate-master
```

Install dependencies:

`npm install`

## Usage

Run dev-server for development, the server will be available at http://localhost:8080/

`npm start`

Build application for production:

`npm run build`
