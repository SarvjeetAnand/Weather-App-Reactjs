# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, we can run:


## Git Clone

```
https://github.com/SarvjeetAnand/Weather-App-Reactjs.git
```
# Installed Library

We have must installed nodejs in our system


## Install React Feather library

React Feather is a lightweight library for icons, and it's excellent for integrating simple and clean icons into our React applications. Here's how we can use React Feather for icons like search, map, and wind:

Installation: First, we need to install React Feather in our project. we can do this via npm.

```
npm install react-feather
```

## Install React dateformat library

We are referring to the `dateformat` library in React, which is actually a JavaScript library commonly used for date formatting in Node.js and browser environments.

Installation: we can install the dateformat library via npm 

```
npm install dateformat
```

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in our browser.

The page will reload when we make changes.\
we may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
our app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once we `eject`, we can't go back!**

If we aren't satisfied with the build tool and configuration choices, we can `eject` at any time. This command will remove the single build dependency from our project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into our project so we have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so we can tweak them. At this point we're on our own.

we don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and we shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if we couldn't customize it when we are ready for it.




## Open weather API

The OpenWeather API is commonly used to fetch real-time weather data based on city names. Developers can integrate this API into their applications to retrieve information such as temperature, humidity, wind speed, and more for a specific location. This data can then be displayed to users or utilized for various purposes within the application.

To use the OpenWeather API's Current Weather Data endpoint, we first need to create an account on the OpenWeather platform and obtain an API key. Here's how we can do it:

1.Create an Account: Go to the OpenWeather website (https://openweathermap.org/) and sign up for a free account if we haven't already.

2.Generate API Key: After creating an account and logging in, navigate to wer account dashboard. Look for the section where we can generate an API key. It might be labeled as "API Keys" or something similar.

3.Get wer API Key: Once we're in the API Keys section, we'll typically find an option to generate a new API key. Click on that and follow any prompts. After generating the API key, make sure to copy it or save it somewhere safe, as we'll need it to make API requests.

4.Using the API Key: Now that we have wer API key, we can use it to access the Current Weather Data endpoint provided by OpenWeather. When making requests to this endpoint, we'll include wer API key as a parameter to authenticate wer requests.

Here's an example of how you make a request to fetch the current weather data for a specific city using the API key:

```
GET https://api.openweathermap.org/data/2.5/weather?q={city}&appid={our_api_key}
```

Replace {city} with the name of the city we want to fetch the weather for, and {our_api_key} with our actual API key.