# Full Stack App: React, Spring Boot, MySQL WorkBench

Inspired by [this video](https://www.youtube.com/watch?v=4LZKnegAm4g)

## Setup Instructions: Front End

`cd` to the correct directory
`npm install`
`npm start`

## Setup Instructions: Back End

Right click, run as, maven clean

Right click, run as, maven install

Right click, run as, spring boot app

## Setup Instructions: Database

In order to run MySQL Workbench, you need to install MySQL Server! These are 2 separate things!

MySQL Workbench: https://dev.mysql.com/downloads/workbench/

MySQL Community Server: https://dev.mysql.com/downloads/mysql/

MySQL Workbench is a GUI for MySQL Server

MySQL Server is the actual database

MySQL Workbench Example

Click server, startup/shutdown, start server

Enter the following queries and execute them one by one:
`create database fullstack;`
`show databases;`
`use fullstack;`
`show tables;`
`desc user;` (description user)
`select * from user;`

Click on Schemas on left side bottom, refresh, and you will see the database

## Connect Back End to Database

In MySQL Workbench, click server, sever status, the port is the shown here, default is 3306

In Spring Tool Suite, application.properties, the datasource.url = jdbc:mysql://localhost:3306/fullstack where 3306 is the port and fullstack is the database name

## Connect Back End to Front end

In Spring Tool Suite, right click, run as, spring boot app, the console will show the tomcat port for the back end, default is 8080

In VSCode, npm install and start, the console will show the port for front end, default is 3000
