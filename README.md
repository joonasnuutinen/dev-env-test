# dev-env-test
A test development environment with a WordPress plugin and a Node API

## Installation

```
git clone --recursive git@github.com:joonasnuutinen/dev-env-test.git
npm install
```

This clones the repository as well as two Git submodules: `node-api-test`and `wp-plugin-test` and then runs `npm install` on all of these.

## Run the development environment

```
npm start
```

## Stop the development environment

First, press `Ctrl/Cmd + C` to stop the Node.js server. Then, run

```
npm stop
```

to stop the WordPress server.
