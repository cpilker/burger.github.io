# burger.github.io

## Purpose
* This program uses node express and handlebars.js functionalities to run a local server for users to create a burger they would like to eat and then devour it after it was created (through an input). The base data is located in the seeds.sql file located at <db/seeds.sql>.

## *How to Use*
* Customers must have the following npm packages installed:
    * Express
    * Body-parser
    * Path
    * My SQL
    * (Node of course)

* Upon downloading the modules, ensure your local server is running (no SQL database is required):
    * Open the local host URL displayed: http://locahost:8080
    * Select data should already be displayed
    * If you would like to eat one of the existing burgers (if any remain), select the *DEVOUR IT!* button.
    * If a burger does not exist, input the name of the burger you would like in the input field & select *SUBMIT*
        * The burger will appear in the left column with the corresponding db ID, name of burger, and option to devour it. 
        * Once devoured the burger cannot be remade in the database, a new one must be created.

* All UI is contained within the handlebars files and no information is appended through jquery, etc. Handlebars are used to give the page a structure and then continue repeating that structure.
* CSS is controlling select aspects of the UI, with a predominance controlled through Bootstrap 4.1.
* ORM files are utilized to obtain appropriate data, and push new data to the db/UI.
