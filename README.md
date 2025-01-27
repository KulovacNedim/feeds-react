﻿## [feeds-react (click to see demo)](https://feeds-react.herokuapp.com/)

[NodeJS - The Complete Guide (incl. MVC, REST APIs, GraphQL) | Udemy](https://www.udemy.com/course/nodejs-the-complete-guide/)

<img src="feeds.PNG" title="shop" alt="feeds.PNG">


## DEMO
[Click to see application in action](https://feeds-react.herokuapp.com/)

Application is deployed to Heroku using it's free hosting plan and Heroku will put it to sleep after some period of inactivity. The backend application will be sleepeng as well. So it is possible that first load of application will be slow (Heroku has to deploy it again).

Also that is the reason why [backend application's repository](https://github.com/KulovacNedim/feeds-rest) contains certain images and why `util/heroku-db-normalizer.js` file is used (to prevent fetching image urls from database without images on server).

## Disclaimer

Code base for frontend (this repository) is not mine. Most of it I got as starting files in [course](https://www.udemy.com/course/nodejs-the-complete-guide/) and during the course I upgrated to be consistent with my [backend Node application](https://github.com/KulovacNedim/feeds-rest).

## Clone

Clone this repo to your local machine using `https://github.com/KulovacNedim/feeds-react.git`
and run `npm init` to install all dependencies

## Available Scripts

In the project directory, you can run:

#### `npm start` - to start the app in production mode
#### `build` - to build the project
