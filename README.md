# socket-io-react-native-chatapp
A chatapp using Socket.io and React Native

After cloning repo from the terminal
`cd server`
`nodemon index.js`
Open a new terminal window while the node server runs
`cd mobile`
`react-native run-ios`
In order to run in android go to line 16 to the App.js in Mobile and replace localhost with your actual ip address in the line `this.socket = io("http://localhost:3000");`
