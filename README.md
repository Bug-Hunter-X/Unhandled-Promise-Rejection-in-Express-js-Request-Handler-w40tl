# Unhandled Promise Rejection in Express.js Request Handler

This repository demonstrates a common error in Node.js Express.js applications: unhandled promise rejections within request handlers.  When an asynchronous operation in a route handler throws an error without proper error handling, the server might not respond to the client request and continues to run without indication. 

The `bug.js` file shows the problematic code. The `bugSolution.js` file shows how to properly handle the error.