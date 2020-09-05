## Weather-App using React
  This project is developed using React.js

 # Description:
      This is basically a Responsive web application in which I have used API to get date related to cities and countries entered by User.

  # Tools and Technologies used:
  1)JavaScript(React)
  2)BootStrap
  3)OpenWeathermap API(current weather data)
  

 # Description Of API used in this Project:
    OpenWeathermap API(current weather data)
    1.Access current weather data for any location 
    2.including over 200,000 cities
    3.Current weather is frequently updated based on   global models and data from more than 40,000 weather stations
    4.JSON, XML, and HTML formats
    5.Available for both Free and paid subscriptions



 # Working:
    As soon as User enters Credentials for City and Country and hit the getWeather button following things are being executed:
    1)Perticular values from city and country textbox are given to the API Call along with unique API Key
    api call is as follows:
    `https://api.openweathermap.org/data/2.5/weather?q=${city},${country}&appid=${Api_Key}`
    2)API returns the value in JSON Format 
    3)perticular values required among huge data are being fetched and set to variables that we are going to use to show:
       CITY,COUNTRY,WEATHER-ICON,TEMPERATURE(Current),Minimum Temperature,Maximum Temperature
     on the Main page itself.
     4)InCase of No-Input the javascript Alert function is used to pop that no inputs given so far.
    

    Hope you will like this Project!!
    Happy Coding!!

    
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
