# Expo Web Native Module Runtime Error

This repository demonstrates a common issue when developing Expo applications that utilize native modules in a web environment.

The problem arises when attempting to access native modules (such as those related to camera, location, or other device-specific functionalities) in a web browser context.  While Expo generally handles this well, it may not always surface explicit errors during development, leading to runtime exceptions.

The `web-native-module-error.js` file showcases the problematic code, which attempts to access a native module that isn't available on web.  The solution, found in `web-native-module-solution.js`, provides a workaround to gracefully handle such scenarios.

## Reproducing the Error

1. Clone this repository.
2. Run `npm install`.
3. Run `expo start`.
4. Open the web browser version of your application.  Observe that a runtime error will occur.