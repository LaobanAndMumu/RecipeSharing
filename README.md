# Recipe Sharing App
This project, created with *create-react-app*, is imoplemented with React. Then this project uses Progressive Web App to implement native-app features: add to home button, push notification, and offline synchronization. 

## File Structure

```
package.json

|---public

|---src

    index.js
    serviceWorker.js
    
    |---components
    
    |---firebase
    
|---functions
```

## Prerequisites
Node.js

## Install
To install all the dependencies 
  ```
  npm install
  ```

## Build
To make a build directory for all files

  ```
  npm run build
  ```

## Usage
To run the project locally

  ```
  npm start
  ```

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
