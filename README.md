# Description:
This code is a website that registers and login users. Once login, the user can see everyone else message and add their own (only one per user). 
If anyone want try this code, [please click at this link](https://secrets--app.herokuapp.com/secrets).

# Tools:
EJS, Node.JS, Node Express, Passport, Google Outh 2.0, MongoDB, Mongoose

# Steps to get code to run:
1. Open terminal
2. Type (You can also download the code):
```
git clone https://github.com/juliorojas81871/secrets
```
3. Make sure that you are in the right folder, if not cd to it.

4. Type in cmd: 
```
npm install
```
5. Make sure you go to the .env to replace the client key and secrets for the Google API. You could also add the MongoDB Atlas URL to the MONGO_URL, but you don't need to since it can run locally too. If you want to use the .env-example file, make sure that you rename that file and remove '-example'.
6. Go to app.js to line 62 and uncommit that line. At the same time, delete line 63. The lines should look like this:
```
// callbackURL: "http://localhost:3000/auth/google/secrets",
    callbackURL: "https://secrets--app.herokuapp.com/auth/google/secrets",
```
7. Type in cmd: 
```
nodemon app.js
```
8. Go to browser and type at the address bar: 
```
http://localhost:3000/
```

# Example Pic:
![Notes Example Pic](https://github.com/juliorojas81871/secrets/blob/main/pics/main.jpg))
