# express-locallibrary

"Local Library" website written in in Node/Express.

---

This web application creates an online catalog for a small local library, where users can browse available books and manage their accounts.

> **Note** The [auth branch](/../../tree/auth) in this repository implements an _unsupported_ and _undocumented_ version of the library with User Authentication and Authorization. This may be a useful starting point for some users.

## Quick Start

To get this project up and running locally on your computer:

1. Set up a [Node.js]
2. Once you have node setup install the project in the root of your clone of this repo:

   ```bash
   npm install
   ```
3. Run the tutorial server, using the appropriate command line shell for your environment:

   ```bash
   # Linux terminal
   DEBUG=express-locallibrary:* npm run devstart
   
   # Windows Powershell
   $ENV:DEBUG = "express-locallibrary:*"; npm start
   ```
4. Open a browser to <http://localhost:3000/> to open the library site.


