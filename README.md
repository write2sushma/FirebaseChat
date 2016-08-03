# FirebaseChat
Project is deployed at: https://awesometechmakers.firebaseapp.com/

Instructions for setting up firebase in your PC can be found from the below link:
https://firebase.google.com/docs/web/setup
(You need to install Node.js before setting up firebase)

Basic steps -

1. Create a new project in firebase using console website - https://console.firebase.google.com/
2. Create a folder in PC
3. Launch Node.js command prompt and install firebase CLI by running below command -
npm install -g firebase-tools

4. Navigate to new folder from Node.js prompt and run below command to initialise firebase
firebase init
(This will ask you to chose a project for deployment. Use the project name that was created using website. After some more questions, this command will create a json file, index.html and folder will be ready.)

5. Copy all the content (css, img  from folder nd index.html)
6. Deploy the content using below command -
firebase deploy

