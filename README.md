<h1 align="center">ExpressJS - Tickitz Booking Ticket RESTFUL API</h1>

This is the API that i created for Tickitz Booking Ticket app. This API is tested by me to make sure this code on API works for project. [More about Express](https://en.wikipedia.org/wiki/Express.js)

## Built With

[![Express.js](https://img.shields.io/badge/Express.js-4.x-orange.svg?style=rounded-square)](https://expressjs.com/en/starter/installing.html)
[![Node.js](https://img.shields.io/badge/Node.js-v.12.13-green.svg?style=rounded-square)](https://nodejs.org/)

## Requirements

1. <a href="https://nodejs.org/en/download/">Node Js</a>
2. Node_modules
3. <a href="https://www.getpostman.com/">Postman</a>
4. Web Server (ex. localhost)

## How to run the app ?

1. Open app's directory in CMD or Terminal
2. Type `npm install`
3. Make new file a called **.env**, set up first [here](#set-up-env-file)
4. Turn on Web Server and MySQL can using Third-party tool like xampp, etc.
5. Create a database with the name #nama_database, and Import file sql to **phpmyadmin**
6. Open Postman desktop application or Chrome web app extension that has installed before
7. Choose HTTP Method and enter request url.(ex. localhost:3000/)
8. You can see all the end point [here](https://documenter.getpostman.com/view/14780095/Tzm6nc1o)
9. Type `npm run dev` to activated the server.

## Set up .env file

Open .env file on your favorite code editor, and copy paste this code below :

```
DATABASE_PORT = <YOUR SERVER PORT>
DATABASE = <YOUR DATABASE NAME>
DATABASE_HOST = <YOUR DATABASE HOST. EXAMPLE: localhost>
DATABASE_USER = <YOUR DATABASE USERNAME. EXAMPLE: root>
DATABASE_PASSWORD = <YOUR DATABASE PASSWORD>

SMTP_EMAIL = <YOUR EMAIL>
SMTP_PASSWORD = <YOUR PASSWORD>
```

## License

© [Muhammad Akbar Saladin Siregar](https://github.com/akbarsaladin36/)