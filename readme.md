# Ionic Tutorial

In this tutorial, you learn how to build a native-like mobile application with Ionic and AngularJS. You build a Conference application that allows the attendees of the conference to browse through the list of sessions, and share information on Facebook.

Follow the step-by-step instructions available here: http://ccoenraets.github.io/ionic-tutorial/
# Introduction

This is a little demo project to show how to implement a hybrid application with the [Ionic Framework](http://ionicframework.com/).

# How to start

```bash
# Fetch the source code
git clone https://github.com/tkssharma/Ionic-Conf.git
cd Ionic-Weather-Application

# If you don't have gulp, bower, ionic and cordova installed, run the following command
npm install -g gulp bower ionic cordova

# Install all necessary tools, plugins and platforms by running the following commands
npm install
ionic state restore
gulp

# Option 1: Run the application on your Android device
gulp run.android

# Option 2: Run the application on your iOS device
gulp run.ios

# Option 4: Build the iOS application (and create the missing icons and splash screen)
ionic resources
gulp build.ios

# Option 4: Build the Android application (no need to create the icons and the splash screen, they are already there)
gulp build.android

# Option 5: Run the UI in your browser (Caution: You won't have device specific features when doing so (e.g. splash screen, device information (the whole about screen will not work!),...)
ionic serve --lab
```

