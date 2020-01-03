# DemoAppSmileIdentity
Demo React Native app for the Smile Identity cross-platform Library

## React Setup (Important)
```
Run `npm i` to install dependencies. This must be done before any other setup.
```
## Android Setup:
```
* Navigate to the android subdirectory
* Open the project on Android studio
* Follow the instructions on [the Official Guide](https://developer.android.com/studio/projects/android-library#AddDependency) how to import the Smile Identity Library provided by the official website.
Build and run! :)
```
## iOS Setup:

#### -  Navigate to the ios subdirectory
#### -  Run pod install.
```
Add the SmileIdentity framework as shown below.
```
![alt text](https://user-images.githubusercontent.com/13585693/71706727-0bfc4980-2de7-11ea-81d0-38d0164f6574.png "Adding Framework")

#### -  Go to Project > Targets > Frameworks/ Libraries/Embedded content
```
Ensure the Smile Identity Framework has "Embed and Sign" option selected.
```
![alt text](https://user-images.githubusercontent.com/13585693/71706723-0b63b300-2de7-11ea-9cf3-85618a695db8.png "Embedding Framework")

#### -  Navigate to the "react-native-smile-identity" Pod
```
Add `${PROJECT_DIR}/../` as a Framework Header Search path.
```
![alt text](https://user-images.githubusercontent.com/13585693/71706726-0bfc4980-2de7-11ea-9030-6361353b3fc0.png "Embedding Framework")

##Voila!


## Authors

* **Oyeleke Okiki** - *Initial work* - [Yeet!](https://github.com/prosquid1)
* **OJ** - *Initial work* - [OJ!](mailto:oj@piggyvest.com)


