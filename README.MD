#Staring application

#One time installation
##To install npm packages
`npm install`

##To start with the database.
`CREATE DATABASE todo;`
`USE todo;`
`CREATE TABLE `todo_list` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `name` varchar(100) NOT NULL,
  `date` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=3 DEFAULT CHARSET=utf8;`

------------------------------------------------------------------------------------

#Start application
##To start the application in the terminal:
`node app.js`
##To start the application with logs file
`node app.js > stdout.txt 2> stderr.txt &`

##To test the API:
GET: http://localhost:8000/todo
POST: http://localhost:8000/todo
PUT: http://localhost:8000/todo
DELETE: http://localhost:8000/todo

##Best import from postman test script:
https://www.getpostman.com/collections/68d49cf995ded19baffb

