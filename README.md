<p align="center">
    <a href="https://github.com/luixaviles/socket-io-typescript-chat">
        <img src="https://img.shields.io/github/stars/luixaviles/socket-io-typescript-chat.svg?style=social&label=Star" alt="GitHub stars">
    </a>
</p>

A Socket.io Chat Example Using TypeScript
=========================================

This repository contains server & client side code using `TypeScript` language

# Support this project
- Star GitHub repository :star:
- Create pull requests, submit bugs or suggest new features

# Running Server and Client locally
## Prerequisites

First, ensure you have the following installed:

1. NodeJS - Download and Install latest version of Node: [NodeJS]
2. Git - Download and Install [Git]
3. Angular CLI - Install Command Line Interface for Angular [https://cli.angular.io/]

After that, use `Git bash` to run all commands if you are on Windows platform.

## Clone repository

In order to start the project use:

```bash
$ git clone https://github.com/luixaviles/socket-io-typescript-chat.git
$ cd socket-io-typescript-chat
```

## Run Server

To run server locally, just install dependencies and run `gulp` task to create a build:

```bash
$ cd server
$ npm install -g gulp-cli
$ npm install
$ gulp build
$ npm start
```

The `socket.io` server will be running on port `8080`

When you run `npm start`, this folder leverages [nodemon](https://nodemon.io/) which will automatically reload the server after you make a change and save your Typescript file. Along with nodemon, there is also a `gulp watch` task that you can run to reload the files but it's not necessary and is provided merely as a teaching alternative. 

## Run Angular Client

Open other command line window and run following commands:

```bash
$ cd client
$ npm install
$ ng serve
```

Now open your browser in following URL: [http://localhost:4200](http://localhost:4200/)

