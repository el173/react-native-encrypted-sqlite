# react-native-encrypted-sqlite

## Getting started

`$ npm install react-native-encrypted-sqlite --save`

### Mostly automatic installation

`$ react-native link react-native-encrypted-sqlite`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-encrypted-sqlite` and add `EncryptedSqlite.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libEncryptedSqlite.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.EncryptedSqlitePackage;` to the imports at the top of the file
  - Add `new EncryptedSqlitePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-encrypted-sqlite'
  	project(':react-native-encrypted-sqlite').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-encrypted-sqlite/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-encrypted-sqlite')
  	```


## Usage
```javascript
import EncryptedSqlite from 'react-native-encrypted-sqlite';

// TODO: What to do with the module?
EncryptedSqlite;
```
