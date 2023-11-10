# POS Server API Readme

## Overview

Welcome to the POS Server API for alfa e-commerce system ! This API provides services to support the functionality of the e-commerce application. Below is information on the setup, dependencies, and how to run the server.

Setup
Clone the repository:

``` bash
Copy code
git clone https://github.com/your-username/pos-api.git
```

cd pos-api
Install dependencies:

```
bash
Copy code
npm install
```

## Import the database

Make sure you have a MySQL server running. Import the database schema provided in the database.sql file to set up the necessary tables.

Create a .env file:

Create a .env file in the root directory with the following variables:

DB_HOST=

DB_USERNAME=

DB_PASSWORD=

BD_NAME=pos_db

PORT=3000
Replace your_password with your MySQL password.

Running the Server
To start the server, run:

```
bash
Copy code
npm run dev
```

The server will be running at <http://localhost:3000>.
