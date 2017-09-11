
# react-native-socket-io

## Getting started

`$ npm install react-native-socket-io --save`

### Mostly automatic installation

`$ react-native link react-native-socket-io`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-socket-io` and add `RNSocketIo.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNSocketIo.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNSocketIoPackage;` to the imports at the top of the file
  - Add `new RNSocketIoPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-socket-io'
  	project(':react-native-socket-io').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-socket-io/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-socket-io')
  	```


## Usage
```javascript
import RNSocketIo from 'react-native-socket-io';

// TODO: What to do with the module?
RNSocketIo;
```
  