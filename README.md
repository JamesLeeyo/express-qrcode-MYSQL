# Project Title

Express-qrocde-mysql



This is a platform that combine MySQL + express + qrcode

## Getting Started

### step 1:
----------------------
      Download the  MySQL database, nodejs 
  
    
### step 2:   
----------------------
    build environment (for ejs)
 
 ```
  express -e
 ```
 ```
  npm install
 ```
  install my SQL package for node.js
 ```
  npm install mysql
 ```
     
### step 3:   
----------------------
  CREATE MYSQL Database 
 ```
  Datbase: test
  table: test
  column: id -> int
 ```
 ### step 4:   
----------------------
 set your MySQL config
 ```
var mysql = require("mysql");

var con = mysql.createConnection({
    host: "localhost",
    user: "root",
    password: "yourpassword",
	  port:'yourport',
    database: "yourdatabase"
});

 ```
   
## Running the tests

npm start




