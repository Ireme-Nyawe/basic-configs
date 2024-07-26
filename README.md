# basic-configs

## babelConfig

[Configure Babel for Node.js Application](https://dev.to/adebayoileri/configure-babel-for-nodejs-application-3798)

## Sequelize Config

[Rest APIs Example with Sequelize ORM](https://dev.to/julfikarhaidar/rest-apis-example-with-sequelize-orm-with-node-js-and-express-p40)  
[Creating Sequelize Associations with the Sequelize CLI Tool](https://levelup.gitconnected.com/creating-sequelize-associations-with-the-sequelize-cli-tool-d83caa902233)

## Sequelize Path Setting

```javascript
const path = require("path");

module.exports = {
  config: path.resolve("./src/db/config", "config.js"),
  "models-path": path.resolve("./src/db/models"),
  "seeders-path": path.resolve("./src/db/seeders"),
  "migrations-path": path.resolve("./src/db/migrations"),
};
