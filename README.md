## Install & Build

First, make sure you have Expo CLI installed: `npm install -g expo-cli`

Install: `yarn` or `yarn install`

Run Project Locally: `yarn dev` or `yarn start`

## Features

- Expo SDK 43
- iOS, Android and PWA (Web App)
- PropTypes

## Expo Web

Currently Expo Web support is **not production ready**, but if you want to see how this project looks on the web as a PWA (Progressive Web App)... using [react-native-web](https://github.com/necolas/react-native-web) and react-dom.

[PWA: Expo Spotify](https://expo-spotify.calebnance.now.sh) looks best on a mobile device, but not bad on desktop!

**Dev with Expo Web**
- Remove node_modules if they exist: `rm -rf nodes_modules`
- Install/Re-install: `yarn`
- Start development: `yarn web` or `expo start --web`
- Build PWA: `yarn web-build` or `expo build:web`
  - Custom Bar for Music Player added to `<BottomTabBar />`
- Modals (bottom to top)
  - Music Player
