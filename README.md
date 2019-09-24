# Node-Twitter-Starter <br>

This repo is a simple NodeJS application that uses twitter's javascript api. It should serve as a lightweight boiler plate to be be used with frontend frameworks like React and Angular to create larger web apps that use twitter data. <br><br>

To get started, make sure you have Node downloaded. If you don't, go to https://nodejs.org/en/download/ <br><br>


Then, you have to create a twitter developer account if you don't have one already. Go here https://developer.twitter.com/, and follow the steps until you can create an account, then go to https://developer.twitter.com/en/account/environments and set up a dev environment, then finally grab your api keys (you'll need consumer key, consumer secret, access key, and access secret). These keys are used to make requests for data. <br><br>


Next, when your in this repo, run the following command <br> npm i express twitter dotenv <br><br>


This will install the dependencies needed to run this example. <br><br>


Next, copy your api keys from twitter into their corresponding variables in the config.env file. <br><br>


Finally, to run the app and test it, run the following command <br>
npm start


This will start the server on localhost:4000 <br><br>


To run my get user timeline example, navigate to localhost:4000/tweets  . This will get Nasa's most recent tweets, then log them in the console. <br><br>


To extend/change the tweet query, just change the server.js file. <br><br>

If you have questions, send me an email at scottmillabeats@gmail.com and I will do my best to help you out :]
