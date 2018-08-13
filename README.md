#Sequelized Burger app#

This app is a remake of the previous Handlebars burger devourer app using Sequelize.

##How to install##

To run it locally, git clone this repository to your machine. Then open the directory in Terminal/Bash and **npm install** the package.json.

##Database##

You'll need to create a MYSQL database. Open your MySQL client and paste in the first 5 lines from the **schema.sql** file in the **db** folder.

##How to run##

Once you've installed the npm packages and created the database, type **node server.js** in terminal/bash. This will run a local server on your machine. In your browser, navigate to **localhost:8080** to view the app.

##What it does**

From here, you can choose to "devour" any of the burgers, switching their status to "devoured."  You can also use the form to create new burgers, which you can then devour.