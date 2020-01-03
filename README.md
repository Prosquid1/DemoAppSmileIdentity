# DemoAppSmileIdentity
Demo React Native app for the Smile Identity cross-platform Library

## React Setup (Important)
```
Run `npm i` to install dependencies. This must be done before any other setup.
```
## Android Setup:
```
Navigate to the android subdirectory
Open the project on Android studio
Follow the instructions on https://developer.android.com/studio/projects/android-library#AddDependency to import the Smile Identity Library provided by the official website.
Build and run! :)

```
## iOS Setup:
```
Navigate to the ios subdirectory (Take note of the iOS path e.g "Users/Prosquid/..../DemoSmileAppIdentity/ios")
Run pod install.
Add the SmileIdentity framework to the root (in Step 1) of the project (Select Copy Files when adding )

```
Go to Project > Targets > Frameworks/ Libraries/Embedded content
Ensure the Smile Identity Framework has "Embed and Sign" option selected.
![alt text](https://user-images.githubusercontent.com/13585693/71705875-d99c1d80-2de1-11ea-9366-330d71aba978.png "Logo Title Text 1")
```

Navigate to the "react-native-smile-identity" Add the iOS path (in Step 1) as a Framework Header Search path.
```
Voila!


