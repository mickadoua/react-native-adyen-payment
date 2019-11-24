# react-native-adyen-payment -- Work In Progress

## Requirements
  1. React Native > 0.60
  2. XCode 11

## Getting started

`$ npm install react-native-adyen-payment --save`

### Mostly automatic installation

`$ react-native link react-native-adyen-payment`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-adyen-payment` and add `AdyenPayment.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libAdyenPayment.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.AdyenPaymentPackage;` to the imports at the top of the file
  - Add `new AdyenPaymentPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-adyen-payment'
  	project(':react-native-adyen-payment').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-adyen-payment/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-adyen-payment')
  	```

### Additional Setup

#### iOS


#### Android

## Usage
```javascript
import AdyenPayment from 'react-native-adyen-payment';

// TODO: What to do with the module?
AdyenPayment;
```