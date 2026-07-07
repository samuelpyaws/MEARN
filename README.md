# MEARN

JavaScript runs in the browser.
Node.js allows JavaScript to run on the server.
Node.js can:
Read files
Connect MongoDB
Create APIs
Handle requests

#Example
console.log("Hello Node");
Run:
node app.js

#STUDENT LETS COME TO PHASE 2:
EXPRESS JS?
express is framework build on node.js.
If you got error in installation.Recovery issue.
<img width="516" height="200" alt="image" src="https://github.com/user-attachments/assets/45a6664c-f91f-4e15-95d7-5a0171a23a63" />
// Import the built-in HTTP module.
// 'http' allows Node.js to create web servers.
const http = require('http');

// Create a server.
// createServer() accepts a callback function.
// This function runs every time a client (browser) sends a request.
const server = http.createServer((req, res) => {

    // req  -> Request object
    //        Contains information sent by the client
    //        (URL, method, headers, etc.)

    // res  -> Response object
    //        Used to send data back to the client.

    // Send the HTTP status code and response headers.
    // 200 means "Request Successful".
    // Content-Type tells the browser what type of data is being sent.
    res.writeHead(200, {
        'Content-Type': 'text/plain'
    });

    // Send the response body to the browser.
    // end() also closes the response.
    res.end('Hello World!');
});

// Start the server and listen on port 3000.
// The callback function executes once the server starts successfully.
server.listen(3000, () => {

    // Print a message in the terminal.
    console.log('Server is running on http://localhost:3000');


#PLACEMENTS LEVEL
Questions similar to those commonly reported in interviews at companies such as:

Accenture
Deloitte
Cognizant
Capgemini
IBM
LTIMindtree
TCS Digital
Infosys Specialist
HCL
Product-based startups


#Topics
#Event Loop
#Callback Queue
#Promises
#Async/Await
#Streams
#Buffers
#File System
#HTTP Module
#EventEmitter
#Cluster
#Worker Threads
#Middleware
#Routing
#Router vs App
#Error Handling
#JWT
#Authentication
#Authorization
#REST APIs
#Status Codes
#CORS
#Cookies & Sessions
#Environment Variables
#MongoDB CRUD
#Mongoose
#Aggregation (basic)
#MVC
#Security
#Performance
});

#Without Express:
const http = require("http");
With Express:
const express = require("express");
Express makes routing easy.
