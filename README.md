# e-commerce-backend
Challenge 13 - Object-Relational Mapping (ORM) Challenge: E-commerce Back End

https://courses.bootcampspot.com/courses/2704/assignments/39998?module_item_id=765848


## Acceptance Criteria
<!-- GIVEN a functional Express.js API -->
<!-- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize -->
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
<!-- WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database -->

## Fill Out the API Routes to Perform RESTful CRUD Operations
Fill out the unfinished routes in 
<!-- 1) product-routes.js,  -->
<!-- 2) tag-routes.js, and  -->
3) category-routes.js 

**Be sure to look at your module project's code for syntax help and use your model's column definitions to figure out what req.body will be for POST and PUT routes!**

## Seed the Database
After creating the models and routes, run npm run seed to seed data to your database so that you can test your routes.

## Sync Sequelize to the Database on Server Start
Create the code needed in server.js to sync the Sequelize models to the MySQL database on server start.

### Create ReadMe
Technical Criteria 
- Syncs Sequelize models to a MySQL database on the server start.
- Includes column definitions for all four models outlined in the Challenge instructions.
- Includes model associations outlined in the Challenge instructions.

### Video Demo
- A walkthrough video that demonstrates the functionality of the e-commerce back end must be submitted, and a link to the video should be included in your README file.
- The walkthrough video must show all of the technical acceptance criteria being met.
- The walkthrough video must demonstrate how to create the schema from the MySQL shell.
- The walkthrough video must demonstrate how to seed the database from the command line.
- The walkthrough video must demonstrate how to start the application’s server.
- The walkthrough video must demonstrate GET routes for all categories, all products, and all tags being tested in Insomnia Core.
- The walkthrough video must demonstrate GET routes for a single category, a single product, and a single tag being tested in Insomnia Core.
- The walkthrough video must demonstrate POST, PUT, and DELETE routes for categories, products, and tags being tested in Insomnia Core.

How to Submit the Challenge
- A walkthrough video:
- The URL of the GitHub repository:

