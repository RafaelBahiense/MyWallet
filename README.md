# MyWallet
### Financial management control Web App.

<p align="center">
  <img src="https://github.com/RafaelBahiense/MyWallet-Front/blob/main/public/imgs/screenshot.png">
</p>

<p align="center">
   <a href="https://pokedex-nine-henna.vercel.app/">Click here</a> to acess the App
</p>

## About

This is an web application which helps people meet their life goals through the proper management of financial resources. Below are the implemented features:

- Sign Up
- Login
- Deposit
- Withdrawal
- History
- Account balance

## Technologies

### The following tools and frameworks were used in the construction of the project Frontend:
|HTML|CSS|JavaScript|ReactJS|
|-|-|-|-|
|[<p align="center"><img alt="HTML" width="60px" src="https://static.cdnlogo.com/logos/h/90/html-5.svg" /></p>][html]|[<p align="center"><img alt="CSS3" width="60px" src="https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg" /></p>][css]|[<p align="center"><img alt="ES6" width="60px" src="https://static.cdnlogo.com/logos/j/44/javascript.svg" /></p>][es6]|[<p align="center"><img alt="React" width="60px" src="https://static.cdnlogo.com/logos/r/63/react.svg" /></p>][react]|
|JSX syntax|CSS styling and styled components|ECMAScript 2015 (ES6) features|React is a JavaScript library for building user interfaces, declarative and component-based|
___

### The following tools and frameworks were used in the construction of the project:
|NodeJS|ExpressJS|TypeScript|PostgreSQL|
|-|-|-|-|
|[<p align="center"><img alt="Node" width="70px" src="https://cdn.worldvectorlogo.com/logos/nodejs-icon.svg" /></p>][node]|[<p align="center"><img alt="Express" width="120px" src="https://cdn.worldvectorlogo.com/logos/express-109.svg" /></p>][express]|[<p align="center"><img alt="Typescript" width="60px" src="https://static.cdnlogo.com/logos/t/96/typescript.svg" /></p>][typescript]|[<p align="center"><img alt="TypeOrm" width="80px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/Postgresql_elephant.svg/540px-Postgresql_elephant.svg.png" /></p>][postgresql]|
|Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine|Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications|TypeScript is an open-source language which builds on JavaScript, one of the world’s most used tools, by adding static type definitions|PostgreSQL is a powerful, open source object-relational database|


[html]: https://www.w3schools.com/html/
[css]: https://www.w3schools.com/css/
[es6]: https://262.ecma-international.org/6.0/
[react]: https://reactjs.org/
[node]: https://nodejs.org/en/
[express]: https://expressjs.com/
[typescript]: https://www.typescriptlang.org/
[postgresql]: https://www.postgresql.org/
[Project repo]: https://github.com/RafaelBahiense/Pokedex


## How to run

1. Clone this repository
2. Initialize the submodules
```bash
git submodule init
```
3. Pull the submodules
```bash
git submodule update
```
4. Go to backend
```bash
cd backend
```
5. Install dependencies
```bash
npm i
```
6. Create a PostgresSQL database "your_database_dev" and "your_database_test"
7. rename `example.local.dev.env` -> `local.dev.env` and `example.local.test.env` -> `local.test.env`
8. Config .env files as indicated
9. Run the Backend with
```bash
npm run dev
```
10. Go to frontend
```bash
cd ../frontend
```
11. Install dependencies
```bash
npm i
```
12. rename `example.env` -> `.env`
13. Config .env files as indicated
14. Run the Front with
```bash
npm start
```
15. Finally access http://localhost:3000 on your favorite browser
