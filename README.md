# Ionic2eBook
Ionic2eBook is an ebook reader built with Ionic2, Angular2 and Cordova.

This ebook reader displays each page with CSS multi-column layout. As each page is panned forward, this ebook will page to the next column on the right. Similarly, for each pan backwards, this ebook will page to the next column on the left.

All HTML5 content and CSS styling that can be displayed in CSS multi-column layout can be displayed by this eBook reader.

The advantages of this eBook reader are:
- Ability to track usage statistics using Firebase Analytics. Each pan of a page is tracked.
- Ability to monitize content using AdMob advertisements.
- Runs on both Android and iOS.

## Example Use of This eBook
This eBook is used to publish the following books on the following platforms:
- [iOS, Malaysian Labour Law Abridged](https://itunes.apple.com/pk/app/malaysian-labour-law-abridged/id991514757?mt=8)
- [Android, Malaysian Labour Law Abridged](https://play.google.com/store/apps/details?id=com.singularmosaic.malaysianlabourlaw&hl=en)

## Install Ionic2, Angular2 and Cordova
```
npm install -g cordova ionic
```

## Download The Source Code and Libraries
```
git clone https://github.com/pinocchio-geppetto/ionic2ebook.git
cd ionic2ebook
npm update
```

## Compile and Run on a Web Browser
```
ionic serve
```

## Compile and Run on iOS
1. Install XCode as described in https://cordova.apache.org/docs/en/latest/guide/platforms/ios/.
2. Run `ionic build ios --prod --release`
3. Upload and run the generated app on an iOS device or on an emulator.

## Compile and Run on Android
1. Install AndroidStudio as described in https://cordova.apache.org/docs/en/latest/guide/platforms/android/index.html.
2. Run `ionic build android --prod --release'
3. Upload and run the generated app on an Android device or on an emulator.

# Configuration
Compile the source code into an app on either Android or iOS.

## How to Compile This eBook on Android

## How to Comipile This eBook on iOS

## How to Place Content Into This eBook

## How to Configure Firebase Analytics

## How to Configure Admob

