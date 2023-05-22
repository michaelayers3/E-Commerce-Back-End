[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
 # E-Commerce Back End


    
 ## Description
This application is used to manage an e-commerce site's backend. The application uses Express.js API and Sequelize to interact with a MySQL database. The application also uses dotenv to store sensitive data.        
 ## Table of Contents
 * [Installation](#installation)
 * [Usage](#usage)
 * [License](#license)
 * [Contributing](#contributing)
 * [Tests](#tests)
 * [Questions](#questions)
                
 ## Installation
 All of the necessary dependencies are included in the package.json. To install necessary dependencies, run the following command:            
        
 ```
 npm i
 ```
To create the database, run the following command:            
        
 ```   
 mysql -u root -p
 ```
Enter your password when prompted. Then run the following commands:
```
source schema.sql
```

In order to seed the database, run the following command:
```
node seeds/index.js
```

To start the server, run the following command:
```
node server.js
```

        
 ## Usage
The application can be used to view, add, update, and delete categories, products, and tags. The user can use Insomnia Core to test the routes.
[The following video](VIDEO HERE) demonstrates the application's functionality:
        
 ## License
 MIT
        
 ## Contributing
 edX
 University of Utah
 Jonathan Bejarano      
        
 ## Tests
No tests are included in this application. However, the user can test the routes using Insomnia Core.        
 ## Questions
 If you have any questions, please contact me at michaelgregoryayers@email.com or visit my GitHub page at
        https://github.com/michaelayers3.
    