### Description

This is an example project that runs in both Expo client and also
directly from a build in Xcode/Android studio. Some people want to
have the benefits of being able to work on and quickly share their app
with the Expo client app, but they need some native modules that aren't
available in it. So it's possible to structure your app in a way where
if a native module you use isn't present, it falls back to some other
behavior (maybe it renders nothing if its a view, or noops / returns
some mocked response if it's a function/constant/whatever).

### Run it

1. Clone this project
2. `yarn` in the root
3. `cd ios && pod install`
4. Run the project in Xcode if you want, or run `expo start` in the root and open it in client
