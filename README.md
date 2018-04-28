<!-- [![Coverage Status](https://coveralls.io/repos/github/GiftcardApp/badge.svg?branch=master)](https://coveralls.io/github/GiftcardApp?branch=master) -->

<!-- [gca-logo](./assets/logo-small.png) -->
<!-- # GiftcardApp -->
[David Wheeler](https://github.com/DavidGWheeler) | [Jeff Huisman]()

## Application Summary
TBD


## Overview
### Minimum Viable Product
* Create and login to user accounts based on username, password, and email.
* Users can create card entries which accept input of:
  *  GiftCard provider (required)(pattern validated)
  *  GiftCard number (required)(pattern validated)
  *  Expiration Date (required)(not expired and pattern validated)
  *  Description
  *  Entry title
  *  Photo Upload and bar code processing
* Users can securely enter financial info including Visa, Master Card, Banking, Gpay, PayPal info to accept accrued value.
* Users can track account balances and available balance.
* Users can request to liquidate and delete account.

### Future Opportunities


### Resources
* [Node.js](https://nodejs.org/en/): Server-side JavaScript environment
* [AWS](https://aws.amazon.com/): Upload Photo storage and functionality
* [Mongo DataBase](https://www.mongodb.com/): Maintain user registration data
* [AngularJS](https://angularjs.org/): HTML for web applications
* [Webpack](https://webpack.js.org/): Module bundler
* [Karma](https://karma-runner.github.io/1.0/index.html): Test runner for Angular JS
* [Heroku](https://www.heroku.com): Deployment (Staging Environment)
* [Express](https://expressjs.com/): Middleware functionality
* [Mongoose](http://mongoosejs.com/): Manage asynchronous environment
* [JSON Web Token](https://jwt.io/introduction/): Secure data transmission
* [Bluebird](https://www.npmjs.com/package/bluebird): Promise rendering
* [Body parser](https://www.npmjs.com/package/body-parser-json): Middleware development
* [Debug](https://www.npmjs.com/package/debug): Debugging code process
* [Cors](https://www.npmjs.com/package/cors): Provides Express middleware
* [Error Handler](https://www.npmjs.com/package/error-handler): Create error status
* [Multer](https://www.npmjs.com/package/multer): Handle middleware form data
* [Bcrypt](https://www.npmjs.com/package/bcrypt): Utilized in password hashing processes
* [Request](https://www.npmjs.com/package/request): Utilized in making http calls
* [Request-Promise](https://www.npmjs.com/package/request-promise): Utilize Request and Bluebird in making http calls

* Developer only:
  * [Mocha](https://www.npmjs.com/package/mocha): Testing framework
  * [Chai](https://www.npmjs.com/package/chai): Testing assertions
  * [Chai-http](http://chaijs.com/): Testing with local server environment

## API Endpoints
Deployed endpoint: URL TBD

Note: Application requests will be unsuccessful without essential environment variables.

### Install Node Packages
#### Back End
1. First, `npm i` to download all resources onto the local machine.
2. In terminal, run files using `npm run start`.

#### Front End
1. First, `npm i` to download all resources onto the local machine.
2. In terminal, run files using `npm run build-watch`.

#### MongoDB
1. Open Mongo Shell by entering `mongod --dbpath ./db` in the local machine terminal.
    * Verify shell by receiving localhost assignment in terminal window.
2. In a separate terminal tab, access Mongo environment by entering `mongo`.
2. After creating a db entry (see steps above), you can view the database by entering `show dbs`.
3. After verifying database creation in Step 2, you can enter the database environment by entering `use <database name>`.
4. To view database contents, example `db.users.find()` in tab.
5. To delete database contents, example `db.users.drop()`.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
