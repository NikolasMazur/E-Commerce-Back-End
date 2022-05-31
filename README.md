# E-Commerce Back End
This project was built with NodeJS, Sequilize, Router, and MySQL to provide a back end for a fictional e-commerce site.
## Installation
1. Install NodeJS
2. Install mySQL
3. Copy repository
4. Run `npm install`

## Usage
1. Rename `.env.Example` to `.env`
2. Change `root` to whatever user mySQL is installed to
3. Change `password` to whatever mySQL password is
4. Navigate to `db` directory in terminal
5. Run `mysql -u root -p` (replace `root` with mySQL installation location)
6. Type `SOURCE schema.sql;`
7. Type `Exit`
8. Type `npm run seed`
9. Type `node server.js`

![](./assets/e-commerce_backend.gif)

## Questions
For additional information you can reach out at the GitHub account "NikolasMazur".

## To-do
As of right now the application is missing two components.
1. Fix products `put`