# request-logger

Simple NodeJS server to log requests to console

## Installation

Clone the project, then run

```
npm install
```

## Config

To change the port the app listens on go to [www](./bin/www) and change the following line:

```
var port = normalizePort(process.env.PORT || '<your_port>');
```

or change the PORT environment variable.

## Running the server

```
DEBUG=request-logger:* npm start
```
