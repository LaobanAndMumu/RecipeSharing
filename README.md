# Recipe Sharing App
This project is created with *create-react-app*. Then this project uses Progressive Web App to implement native-app features, add to home button, push notification, and offline synchronization. 

## Install
    npm install

## Build
    npm run build

## Usage
    npm start

## Firebase

This project uses Firebase, Google Cloud Platform, for hosting and database. To deploy the project to Firebase, first need to create a project at Firebase console, then

1. Change Firebase configuration to that of your own project at `src/firebase/firebase.js`

2. At your root directory, install Firebase CLI through npm

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
