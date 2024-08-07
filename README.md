Purpose -
This repository contains a RESTful API designed to manage student records with CRUD (Create, Read, Update, Delete) operations.
The API allows you to perform various operations on student data, making it a useful tool for educational institutions, administrative systems, or any application that requires student data management.

Features -
1) Create: Add new student records to the system.
2) Read: Retrieve details of existing student records.
3) Update: Modify existing student records.
4) Delete: Remove student records from the system.
5) List: Retrieve a list of all students or filter by various criteria.

Technologies Used -
1) Node.js with Express
2) JSON-server
3) Postman desktop app

Local Setup Instructions -
Prerequisites
1) Node.js
2) JSON-server

Setting Up the Environment -
1) Make new directory(crud-RestAPI) with the help of CMD.
2) Change the directory.
3) Install Node.js. with command 'npm install'.
4) Also install express in the package with 'npm i express' command.
5) Create index.json(databaseFileName) file to store the data within same directory. Enter the data in it.
6) Command 'npm init -y' which will create package.json file.
7) Install json-server.
8) Edit package.json file, change inside of the 'Scripts' with ""json-server": "json-server --watch <databaseFileName>".
9) Run 'npm run json:server' command. This will connect system to the local host server.

testing -
1) Now, browse to local host, to see the data created.
2) Editing to local host's link can result to get data with different variations.
3) To test CRUD methods, use Postman Desktop Application.
