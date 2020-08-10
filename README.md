# Simple Ionic app with Cordova plugin

Simple Ionic app build with Cordova plugin.

### Installation
- Install Ionic CLI
  > npm install -g @ionic/cli
- Setup iOS development: https://ionicframework.com/docs/developing/ios
  > npm install -g ios-sim
  > brew install ios-deploy
- Redirect project folder, then run
  > npm install

### Running on iOS
- Sync Ionic app to native project
  > ionic cordova prepare ios
- Open Xcode, route to platform/ios folder, then run project with simulator.
- Live-reload with Cordova
  > ionic cordova run ios -l --external

### Preferences
- https://ionicframework.com/docs/intro/cli
- https://ionicframework.com/docs/developing/ios