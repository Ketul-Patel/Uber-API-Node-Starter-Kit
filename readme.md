# Uber API Node.js Starter Kit 

Use this Starter Kit to connect to the Uber API using Node.js and Express.js

To get started you will first have to register your app via the [Uber developer site](https://developer.uber.com/apps/new). You will need an Uber account to register. After registering keep track of your Client ID, Client Secret, and Server Token as you will have to add them to your config.js file. Also make sure that you set the redirect url to be "http://localhost:8000/auth/uber/callback" in your app settings.

This starter kit does not include a database. Also all of the logic for accessing Uber endpoints is done in one file: server.js. Feel free to add a database and modularize the code if needed.

We use the [sandbox environment](https://developer.uber.com/v1/sandbox/) provided by Uber so that we aren't actually interacting with live uber cars and accidentally charging our users credit cards in development :)

To get this working you will need to 1) Install all of your dependencies using "sudo npm install" then 2) modify the sampleconfig.js file and rename it.

[Uber API Docs](https://developer.uber.com/v1/endpoints/)
