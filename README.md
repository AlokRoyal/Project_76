# Space Explorer — Project 76

![React Native](https://img.shields.io/badge/React_Native-Expo-61DAFB?logo=react&logoColor=black)
![Expo SDK](https://img.shields.io/badge/Expo-SDK%2042-000020?logo=expo&logoColor=white)

An Expo and React Native app organized around a four-screen space exploration flow. The root component registers Home, Star Map, Daily Picture, and Spacecraft screens in a React Navigation stack.

## Features and structure

- Stack navigation with Home as the initial route
- Dedicated screen modules under screens/
- Local application resources in assets/
- Navigation header hidden so screens can control their own presentation

App.js owns the NavigationContainer and route declarations. Screen content is kept outside the root component to make the app structure easier to extend.

## Architecture

Expo entry point → App.js → React Navigation container → screen component selected by route

## Technology

React 16.13, React Native with Expo SDK 42, React Navigation 5, React Native Web, Gesture Handler, Reanimated, Screens, Safe Area Context, and Babel. See package.json for pinned ranges.

## Start locally

    npm install
    npm start

Choose a target with npm run android, npm run ios, or npm run web. Android/iOS runs require a device or emulator. Expo Go compatibility depends on the installed SDK and device environment.

## Project layout

- App.js — navigation container and stack routes
- screens/ — Home, StarMap, DailyPic, and SpaceCraft screen components
- assets/ — app resources
- app.json — Expo application configuration
- package.json — scripts and dependencies
- package-lock.json and yarn.lock — npm and Yarn lockfiles

## Dependency note

Both npm and Yarn lockfiles are checked in. Choose one package manager and keep its lockfile authoritative. No automated test scripts are listed.