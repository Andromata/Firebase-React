# Implementation of Firebase in React

I made this code following a step by step tutorial made by Kyle... you can find the video in his youtube channel "Web Dev Simplified".
Link [React Authentication Crash Course With Firebase And Routing](https://www.youtube.com/watch?v=PKwu15ldZ7k&t=2683s)
I recommend his channel !!! ---> <a href="https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw"><img src="https://image.flaticon.com/icons/png/128/733/733590.png?style=social&amp;maxAge=3600" height="20"></a>


## What will you find here?

You'll find the most common methods of Firebase Auth as signup, login, Logout, update email & password. Also there is an interesting way of using it with React.CreateContext and how to make private routes.


### `yarn install & start`

You can clone the repository and just do yarn install and yarn start to runs the app in the development mode.
By default open [http://localhost:3000](http://localhost:3000) to view it in the browser.
The page will reload if you make edits.
You will also see any lint errors in the console.

### `Initial settings`

You have to create an .env.local file to store all local variables of your firebase configuration, firebase.js will use this data.

```
REACT_APP_FIREBASE_API_KEY=...
REACT_APP_FIREBASE_AUTH_DOMAIN=...
REACT_APP_FIREBASE_PROJECT_ID=...
REACT_APP_FIREBASE_STORAGE_BUCKET=...
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=...
REACT_APP_FIREBASE_APP_ID=...
REACT_APP_FIREBASE_MEASUREMENT_ID=...

```
### Versions

[![REACT version](https://img.shields.io/badge/react-17.0.2-green)](https://yarnpkg.com/package/react)
[![YARN version](https://img.shields.io/badge/yarn-1.22.10-green)](https://yarnpkg.com/package/yarn)
[![Bootstrap version](https://img.shields.io/badge/bootstrap-4.6.0-orange)](https://yarnpkg.com/package/bootstrap)
[![FIREBASE version](https://img.shields.io/badge/firebase-8.4.1-blue)](https://yarnpkg.com/package/firebase)