# GoogleLoginTest

This test app is for the Google OAuth2.0 using a locally run MongoDB, for simplicity. 

To run:
1) STOP here if you don't have the secret file, it won't work
2) Clone repository
3) Run npm install from root directory in your terminal
4) Start up MongoDB (after it is installed)... ( I use the command: " brew services start mongodb-community@4.4")
5) Start the app with the command "node app.js"
6) Open "http://localhost:3000/" in your browser

You will know this works because you won't be able to access http://localhost:3000/secrets without logging in. 
Once you are logged in, you may visit other sites on the world wide web and return to the secrets page and you will still be able to view it (unless you log off).
