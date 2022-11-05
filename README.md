## Important Note!

util/database.js is missing! Create this file before starting

**util/database.js example:**
```
const Sequelize = require("sequelize");

const sequelize = new Sequelize("<database-name>", "root", "<database-password>", {
  dialect: "mysql",
  host: "localhost",
});

module.exports = sequelize;
```
