# App Auth JS Demo App

Simple Web Demo Application protected by OpenID Connect using App Auth JS

## Prerequisites

1. Gluu Server
2. Node JS

## Installation

1. Clone this repo
```
$ git clone https://github.com/ldeveloperl1985/appauth-web-app-demo.git
```

2. Install dependency
```
$ cd appauth-web-app-demo
```
```
$ npm install
```

## Configuration

Use [appauth-util.js](./appauth-util.js#L26) for configuration.

## Run Application

```
$ node_modules/.bin/http-server -p 8000
```

## Tips for SPA technologies

There are so many SPA technologies in market Angular, React, Vue and others.

1. You can use same `appauth-js` in all technologies. 

      Install appauth-js
      
      ```
      $ npm install @openid/appauth
      ```

2. Import the module which you want. Take a [electron demo file here](https://github.com/googlesamples/appauth-js-electron-sample/blob/master/flow.ts) and use it.
