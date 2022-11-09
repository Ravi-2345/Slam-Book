## Slam-Book

- A social media website where registered users can share photos , texts etc with their friends.
- This app allows users to create account , login , logout, create own post , like and dislike any post.
- Also get the collection of all of your posts in your profile.

## signup page
![image](https://user-images.githubusercontent.com/102463812/200878203-d80609d7-0ebe-41fe-bef9-d3006a2256d6.png)

## sign in page
![image](https://user-images.githubusercontent.com/102463812/200878361-c2e921b6-c065-4424-a25a-3d33407a4f21.png)

## Slam-Book user's homepage feeds
![image](https://user-images.githubusercontent.com/102463812/200879826-a827424f-e351-4bad-99de-b969c3339a1a.png)

![image](https://user-images.githubusercontent.com/102463812/200880053-a2edfe29-d655-480b-ac92-157e49be7d37.png)

## User's profile page
![image](https://user-images.githubusercontent.com/102463812/200880176-aaeae2da-f8fc-4e95-98a3-b941edc18f69.png)

## share post
![image](https://user-images.githubusercontent.com/102463812/200880587-10f1c310-7a0d-4335-9f69-fc0cbbc0ce54.png)

<br>

## NPM DEPENDENCIEs (for API) 
```
{
  "name": "rest-api",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "start": "nodemon index.js"
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
    "bcrypt": "^5.0.1",
    "cors": "^2.8.5",
    "dotenv": "^8.2.0",
    "express": "^4.17.1",
    "helmet": "^4.4.1",
    "mongoose": "^5.12.2",
    "morgan": "^1.10.0",
    "multer": "^1.4.4",
    "nodemon": "^2.0.7",
    "path": "^0.12.7"
  }
}
```

## NPM DEPENDENCIES (for CLIENT)
```
{
  "name": "react-social",
  "version": "0.1.0",
  "private": true,
  "dependencies": {
    "@material-ui/core": "^4.11.3",
    "@material-ui/icons": "^4.11.2",
    "@testing-library/jest-dom": "^5.11.4",
    "@testing-library/react": "^11.1.0",
    "@testing-library/user-event": "^12.1.10",
    "axios": "^0.21.1",
    "react": "^17.0.2",
    "react-dom": "^17.0.2",
    "react-router-dom": "^5.3.3",
    "react-scripts": "4.0.3",
    "timeago.js": "^4.0.2",
    "web-vitals": "^1.0.1"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  },
  "eslintConfig": {
    "extends": [
      "react-app",
      "react-app/jest"
    ]
  },
  "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  },
  "proxy": "http://localhost:8800/api"
}
```

## LOCAL ENVIRONMENT SETUP

- Clone repository by running this command on git-bash

```
    git clone https://github.com/<your user-name>/Slam-Book.git
```

- Install Dependencies(for both API and Client) using

```
    npm install
```
- Create the .env file for both API and Client App
   <br> <br>
     -for API  
      put your Mongo Atlas URL as 
         ```
           MONGO_URL= mongo atlas url here
         ```
       <br>
     -for Client 
      put your Mongo Atlas URL as 
         ```
           REACT_APP_PUBLIC_FOLDER = http://localhost:8800/images/
         ```
         
     
       - Add this to `.env` file
  - Please Note, the ATLAS_URI is not the database link of MongoDB Atlas, its just the variable name. The URL is for local use only
  <br>
    
- That's all, now just Sign Up to Slam-Book and be friends forever.
  <br>
  <br>

## CONTRIBUTING

This project is open for contributions so Pull requests and Issues are welcome.
# Slam-Book
