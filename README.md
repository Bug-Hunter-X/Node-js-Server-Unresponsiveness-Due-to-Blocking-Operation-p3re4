# Node.js Server Unresponsiveness

This repository demonstrates a common issue in Node.js applications: server unresponsiveness caused by blocking operations within the request handler.  The `server.js` file contains a simple HTTP server with a computationally intensive loop in its request handler.  This blocks the event loop, preventing the server from processing subsequent requests.

The solution, provided in `serverSolution.js`, demonstrates how to handle such operations asynchronously using promises, or other methods.