# Comunarr file manager client

![Comunarr](https://static.wixstatic.com/media/338ed6_82a0ae1e055844fdb83495390e31c58c.jpg/v1/fill/w_320,h_192,al_c,q_80,usm_0.66_1.00_0.01/338ed6_82a0ae1e055844fdb83495390e31c58c.webp "Comunarr logo")

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

**You need to have installed Node's 6.9.5 version.**
* We recommend you to use [nvm](https://github.com/creationix/nvm) for managing different node versions in MacOS/Linux
* For Windows users there are two alternatives:
    * [nvm-windows](https://github.com/coreybutler/nvm-windows)
    * [nodist](https://github.com/marcelklehr/nodist) - best option

After you are sure of being using 6.9.5 version of Node, you can install all dependencies by running:

```
npm install
```

You can run a dev-server by running
```
// Only in debugging mode
npm start
```

## Deployment

1. Run the follow command in order to install all dependencies
```npm install```

2. Change in the follow file ```src/app/config/environment.config.js``` to set the correct environment, the list of all available environments are located in ```./src/app/common/services/environment.service.js```, you need to replace or add a new one in order to connect to the API

3. After setting up the environment, execute the following command:
```
    npm build
```
This command will create a directory under the root called ```dist```

4. Locate the dist directory in any web server


## Built With 💚 and the following great projects:

* [Angular 1.x](https://angularjs.org/) - Frontend framework
* [NPM](https://www.npmjs.com/) - Dependency management
* [WebPack 2](https://webpack.js.org/) - Used to automate workflow
* [Babel](https://babeljs.io/) - ES2015 transpiler
* [Airbnb JavaScript Style Guide() {](https://github.com/airbnb/javascript) Code style guide
* [Todd Motto's Angular 1.x Style Guide](https://github.com/toddmotto/angular-styleguide) Architecture style guide

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
