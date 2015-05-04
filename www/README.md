This is an addon starter template for the [Ionic Framework](http://ionicframework.com/).

## How to use this template

*This template does not work on its own*. It is missing the Ionic library, and AngularJS.

To use this, either create a new ionic project using the ionic node.js utility, or copy and paste this into an existing Cordova project and download a release of Ionic separately.

### With the Ionic tool:

Take the name after `ionic-starter-`, and that is the name of the template to be used when using the `ionic start` command below:

```bash
$ sudo npm install -g ionic cordova
$ ionic start myApp sidemenu
```

Then, to run it, cd into `myApp` and run:

```bash
$ ionic platform add ios
$ ionic build ios
$ ionic emulate ios
```

Substitute ios for android if not on a Mac, but if you can, the ios development toolchain is a lot easier to work with until you need to do anything custom to Android.

## Demo
http://plnkr.co/edit/0RXSDB?p=preview

## Issues
Issues have been disabled on this repo, if you do find an issue or have a question consider posting it on the [Ionic Forum](http://forum.ionicframework.com/).  Or else if there is truly an error, follow our guidelines for [submitting an issue](http://ionicframework.com/contribute/#issues) to the main Ionic repository. On the other hand, pull requests are welcome here!


cordova plugin add https://github.com/wildabeast/BarcodeScanner.git

#FACBOOK INTEGRATION
cordova plugin add https://github.com/Wizcorp/phonegap-facebook-plugin.git --variable APP_ID="123456789" --variable APP_NAME="myApplication"

#OAuth
cordova plugin add https://git-wip-us.apache.org/repos/asf/cordova-plugin-inappbrowser.git

#get hashes for facebook

keytool -list -alias androiddebugkey -keystore %HOMEPATH%/.android/debug.keystore

pass android
EA:2A:DD:C2:FF:46:22:97:6A:4E:C6:2E:03:7B:17:6B:20:EF:C3:C6


#Para firmar la app

keytool -genkey -v -keystore my-release-key-mascoteros.keystore -alias mascoteros -keyalg RSA -keysize 2048 -validity 90000

Is CN=gerardo grimaldi, OU=mascoteros.net, O=mascoteros, L=buenos aires, ST=buenos aires, C=ar correct?

pass mascoteros

para hacer andar home

export ANDROID_HOME=/Applications/android-sdk-macosx export ANDROID_TOOLS=Applications/android-sdk-macosx/android-sdk/tools/ export ANDROID_PLATFORM_TOOLS=Applications/android-sdk-macosx/platform-tools/ PATH=$PATH:$ANDROID_HOME:$ANDROID_TOOLS:$ANDROID_PLATFORM_TOOLS:.

