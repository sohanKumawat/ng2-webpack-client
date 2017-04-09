# ng2-webpack-client


This is a angular4 client application with webpack-2.x.

This application used to bundle all the app js and css file in single file and extract css file at run time on component level not global level.

I used to styleUrls instead of styles in component.

How to run -

Got to src directory and download all the npm dependency usgin npm install.

After downloading the dependency execute following command as you want.

"scripts": {
    "start": "webpack-dev-server --inline --progress --port 8080",
    "test": "karma start",
    "build": "rimraf dist && webpack --config config/webpack.prod.js --progress --profile --bail"
  },

npm start used to start application in development mode.

npm test used to start application in testing mode.

npm build used to for production deployment.
