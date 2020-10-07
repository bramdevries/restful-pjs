This is an example of how to host your application on Heroku. 

To be able to deploy to Heroku we added a custom `server.js` file that will be started when running `npm start`. 
This server will start the json-server API but also host the files in `public`.