
**What is server?**
A server is a computer or a program that provides services or data to other computers (called clients) over a network.

The command **npm init -y** (or npm init --yes) instantly initializes a new Node.js project by generating a package.json file with standard default configuration values.

npm i express - install express

Node.js is a runtime environment, whereas Express.js is a web application framework built to run inside that environment. 

const app = express(); // here we are creating a instance of express server

app is now the object that you use to:

Create routes
Handle requests
Send responses
Start the server


**API & REST API**
API - It is a set of rules and protocols that lets different software programs talk to each other.

Types of API:


RESTAPI
GET
PATCH
POST
DELETE

Explaination of Folder Structure:
-> server.js = use to start the server
requires app from ./src/app
module.exports = app; // for exporting

./
/src
/app.js = use to create server 
we export app to serevr