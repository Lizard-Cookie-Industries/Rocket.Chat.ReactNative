# Rocket.Chat Mobile, whitelabeled for Secure Utility

[![Project Dependencies](https://david-dm.org/RocketChat/Rocket.Chat.ReactNative.svg)](https://david-dm.org/RocketChat/Rocket.Chat.ReactNative)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/bb15e2392a71473ea59d3f634f35c54e)](https://www.codacy.com/app/RocketChat/Rocket.Chat.ReactNative?utm_source=github.com&utm_medium=referral&utm_content=RocketChat/Rocket.Chat.ReactNative&utm_campaign=badger)
[![codecov](https://codecov.io/gh/RocketChat/Rocket.Chat.ReactNative/branch/master/graph/badge.svg)](https://codecov.io/gh/RocketChat/Rocket.Chat.ReactNative)
[![CodeFactor](https://www.codefactor.io/repository/github/rocketchat/rocket.chat.reactnative/badge)](https://www.codefactor.io/repository/github/rocketchat/rocket.chat.reactnative)

**Supported Server Versions:** 0.70.0+


## Updating from the Upstream

https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork

- basically:
    ```bash
	$ git fetch upstream
	$ git checkout single-server
	$ git merge upstream/master
    ```
	
Then push it to the repository

## Build a release:

https://reactnative.dev/docs/running-on-device
https://reactnative.dev/docs/signed-apk-android

`npx react-native run-android --variant=release

## Download

### Official apps
<a href="https://play.google.com/store/apps/details?id=chat.rocket.android">
  <img alt="Download on Google Play" src="https://play.google.com/intl/en_us/badges/images/badge_new.png" height=43>
</a>
<a href="https://apps.apple.com/us/app/rocket-chat/id1148741252">
  <img alt="Download on App Store" src="https://user-images.githubusercontent.com/7317008/43209852-4ca39622-904b-11e8-8ce1-cdc3aee76ae9.png" height=43>
</a>

### Experimental apps
<a href="https://play.google.com/store/apps/details?id=chat.rocket.reactnative">
  <img alt="Download on Google Play" src="https://play.google.com/intl/en_us/badges/images/badge_new.png" height=43>
</a>
<a href="https://itunes.apple.com/us/app/rocket-chat-experimental/id1272915472">
  <img alt="Download on App Store" src="https://user-images.githubusercontent.com/7317008/43209852-4ca39622-904b-11e8-8ce1-cdc3aee76ae9.png" height=43>
</a>

## Beta Access

### TestFlight

You can signup to our TestFlight builds by accessing these links:

- Official: https://testflight.apple.com/join/3gcYeoMr
- Experimental: https://testflight.apple.com/join/7I3dLCNT.

### Google Play beta

You can subscribe to Google Play Beta program and download latest versions:

- Official: https://play.google.com/store/apps/details?id=chat.rocket.android
- Experimental: https://play.google.com/store/apps/details?id=chat.rocket.reactnative

## Reporting an Issue

[Github Issues](https://github.com/RocketChat/Rocket.Chat.ReactNative/issues) are used to track todos, bugs, feature requests, and more.

Also check the [#react-native](https://open.rocket.chat/channel/react-native) community on [open.rocket.chat](https://open.rocket.chat). We'd like to help.

## Installing dependencies

Follow the [React Native Getting Started Guide](https://facebook.github.io/react-native/docs/getting-started.html) for detailed instructions on setting up your local machine for development.

## How to run
- Clone repository and install dependencies:
    ```bash
    $ git clone git@github.com:RocketChat/Rocket.Chat.ReactNative.git
    $ cd Rocket.Chat.ReactNative
    $ yarn
    ```

- Run application
    ```bash
    $ npx react-native run-ios
    ```
    ```bash
    $ npx react-native run-android
    ```

### Running single server
If you don't need multiple servers, there is a branch `single-server` just for that.
Temp whitelabel docs: https://docs.google.com/document/d/17ib2Le_SH6U2gP0sEuKapF2J-WgqZxPFMRRVUSofz7Y/edit


The default branch is `single-server`
See https://github.com/RocketChat/Rocket.Chat.ReactNative/compare/single-server#diff-6a1b6963e828b69fcc667e3c45df78bb


