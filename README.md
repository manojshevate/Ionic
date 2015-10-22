# Ionic

http://ionicframework.com/docs

Steps:

####Install Cordova CLI
npm install -g cordova

####Install Ionic CLI
npm install -g ionic

####Start new Project
ionic start todo blank

####Add Platform
ionic platform add android

####Build your project
ionic build android

####Test your code in browser
ionic serve

####Remove debug mode
cordova plugin rm cordova-plugin-console

####Release build
cordova build --release android
