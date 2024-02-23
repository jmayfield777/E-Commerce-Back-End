# E-Commerce-Back-End

## Description

This projects serves as the back end for an E-Commerce business that utilizes Express.js. The 'ecommerce_db' database stores all of the data for this mock web store. CRUD routes (using express HTTP methods GET, POST, PUT, and DELETE) were implemented to allow the insertion, deletion, updating, and viewing of the data on the back end. Further code will be needed to ensure that the client can manipulate the data in a similar way in the UI. 

Walkthrough video - https://drive.google.com/file/d/1ZsGtnaUPyeAqdl0KpU6OcsIynmAGDowf/view?usp=sharing


## Table of Contents

 * [Installation](#installation)

 * [Usage](#usage)

 * [Credits](#credits)

 * [License](#license)

 * [Questions](#questions)

## Installation

To run this project, run the following command:


```
npm init 
```


(add "-y" to answer yes to all questions regarding the creation of the package.json), then run the following code to install any necessary dependencies:


```

npm i 
```


Open an instance of MYSQL in a separate tab, navigating to the db folder holding the 'schema.sql' file. Run the following command to create the database:

```
SOURCE schema.sql;

```

You can then quit out of MYSQL with the following command:

```
quit;
```


Navigate back to your main terminal tab and run the following command once you have navigated to the folder holding the server.js file to seed the database:

```
npm run seed
```

Next run this command to connect to the server:

```
npm start
```


## Usage

Clone this repo and save it locally to your computer. Open terminal, git bash, or whichever command line interface you are using and navigate to the directory holding the server.js file. Run the following command:

```
npm start
```

You can then test the various api routes in Insomnia or a similar application.

## Credits

https://sequelize.org/docs/v6/ (help with routes)

https://stackoverflow.com/questions/33989196/using-the-post-method-with-sequelize (help with routes)

https://sequelize.org/docs/v6/core-concepts/model-querying-basics/ (help with routes)

https://sequelize.org/docs/v6/core-concepts/validations-and-constraints/ (help with model validation and constraints)

https://www.bezkoder.com/sequelize-associate-many-to-many/#google_vignette (help with many to many association)

https://stackoverflow.com/questions/29680359/how-to-use-sequelize-belongstomany-associations (help with many to many associations)

https://sequelize.org/docs/v7/associations/belongs-to-many/ (help with belongs to many association)

## License

![License Badge](https://img.shields.io/badge/license-MIT-blue)

## Questions

If you have any questions about this application, please feel free to contact me at my email : josh.mayfield45@gmail.com and Github profile : https://github.com/jmayfield777