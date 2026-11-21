# Space Explorer — Project 76

An Expo and React Native app organized around a four-screen space exploration flow. The root component wraps the app in a React Navigation container and registers Home, Star Map, Daily Picture, and Spacecraft screens.

## Navigation and structure

App.js defines the stack navigator and initial Home route. Screen components live under screens/, while assets/ stores app resources and app.json contains Expo configuration. The navigation header is hidden so each screen can provide its own design.

## Stack

React 16.13, React Native with Expo SDK 42, React Navigation 5, React Native Web, Gesture Handler, Reanimated, Screens, and Safe Area Context.

## Setup and run

    npm install
    npm start

Use npm run android, npm run ios, or npm run web to choose a platform. A device or emulator is required for native targets.

## Dependency note

Both package-lock.json and yarn.lock are present. Choose one package manager and use its lockfile consistently when installing or updating dependencies.