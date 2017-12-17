
# react-native-survey-monkey-sdk

## Getting started

`$ npm install react-native-survey-monkey-sdk --save`

### Mostly automatic installation

`$ react-native link react-native-survey-monkey-sdk`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-survey-monkey-sdk` and add `RNSurveyMonkeySdk.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNSurveyMonkeySdk.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNSurveyMonkeySdkPackage;` to the imports at the top of the file
  - Add `new RNSurveyMonkeySdkPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-survey-monkey-sdk'
  	project(':react-native-survey-monkey-sdk').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-survey-monkey-sdk/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-survey-monkey-sdk')
  	```

## Usage
```javascript
import RNSurveyMonkeySdk from 'react-native-survey-monkey-sdk';

// TODO: What to do with the module?
RNSurveyMonkeySdk;
```
  