# Unhandled Exception in Node.js Main Thread

This repository demonstrates an example of an unhandled exception in the main thread of a Node.js application and its solution.

## Bug

The `bug.js` file contains a simple HTTP server.  However, it lacks error handling, leading to an unhandled exception if an error occurs during request processing.

## Solution

The `bugSolution.js` file demonstrates how to use try...catch blocks to handle potential exceptions and prevent the application from crashing.