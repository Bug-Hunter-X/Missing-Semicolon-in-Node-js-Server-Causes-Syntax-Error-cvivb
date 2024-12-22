# Missing Semicolon in Node.js Server

This repository demonstrates a common yet easily overlooked error in Node.js: a missing semicolon in a console.log statement. This seemingly minor omission can lead to a syntax error that prevents the server from starting.

## Bug

The `bug.js` file contains a Node.js server that intentionally omits a semicolon after a `console.log` statement. This omission causes a syntax error. 

## Solution

The `bugSolution.js` file demonstrates the correct way to write the code. A simple addition of a semicolon fixes the error, allowing the server to run without any issues. 

## How to Reproduce

1. Clone this repository.
2. Navigate to the repository's directory.
3. Run `node bug.js` to observe the error. 
4. Run `node bugSolution.js` to observe the fixed version.