
# Pixi-es6

Bootstraping a Pixi.js project with ES6 features and a complete developpment setup.


## Features

Create or edit the scripts in the "/src/" directory. The javascript build that will be your project is in the file "/src/app.js". 
You can use ES6 features like import and stuff. Don't forget to add /* global PIXI */ when using the PIXI object in your scripts or you will have an ESLint error (See the example "/src/test.js")

Other features:
- ESLint warnings and errors with Babel and recommended javascript configuration
- Watch and build automatically when script is saved
- Notifications on warnings and errors
- BrowserSync
- Express server that opens automatically on http://localhost:3000/ on launch
- The Pixi.js library v4.5.6
- An example to test the Pixi.js library ans ES6 features

In current state, using the Pixi.js v4.5.6, but the version is easy to change, add another version or add a distant script to the latest Pixi.js version in the "/build/index.html" file. 

The server is using the "/build/" directory as root directory.


## Installation

After cloning the prject:

```
npm install
```

To start the server in Developpment mode:
```
npm start
```

To build the production ready javascript:
```
npm run build
```
