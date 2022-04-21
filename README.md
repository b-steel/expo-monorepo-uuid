## UUID package issue in Expo Monorepo

The setup for this project is exactly the same as the one outlined in [Working with Monorepos](https://docs.expo.dev/guides/monorepos/). Running `yarn workspace cool-app start` will start the app and the page looks as expected.  
If you run `yarn workspace cool-app add uuid` then start the app (same method as before) the app is stuck on the splash screen. However if you turn on "debug remote JS" then the app works as intended. Running in production mode also works fine.

Seems to be similar to [#15035](https://github.com/expo/expo/issues/15035)

`expo-cli` version `5.3.2`
