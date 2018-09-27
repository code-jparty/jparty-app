# JParty-App

Frontend for JParty: A webapp in TypeScript+React packaged with Apache Cordova.

## Getting started

- Download and install [Node.js](https://nodejs.org/en/download/)
- Install Cordova: `npm install -g cordova`
- Clone the project and switch into its directory
- Add platforms: `cordova platform add browser android `
  - On Mac, also add ios: `cordova platform add ios`

For futher information, refer to the
[Cordova setup guide](https://cordova.apache.org/docs/en/latest/guide/cli/index.html)

## Commands

command | effect
----|---
`npm start` | opens the application in the browser
`npm run android` | opens the application on an android device
`npm run ios` | opens the application on an ios device
`npm run clean` | removes all compilation output and downloaded modules