# RecipeSharing
Created with *create-react-app*


## Install
    npm install

## Build
    npm run build


## Usage
    npm start

## Firebase

This project uses Firebase, Google Cloud Platform, for hosting and database. To deploy the project to Firebase, first need to create a project at Firebase console, then

1. Change Firebase configuration to that of your own project at `src/firebase/firebase.js`

2. Install Firebase CLI through npm

    ```
    npm install -g firebase-tools
    
    ```

3. Initialize the project 

    ```
    firebase init
    
    ```

4. Deploy the project to Firebase 

    ```
    firebase deploy
    
    ```
