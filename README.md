Test [Cordova BLE plugin](https://github.com/don/cordova-plugin-ble-central) with Ionic

    ionic platform add android
    ionic plugin add cordova-plugin-ble-central
    ionic run
    
If your device is running Android 6, edit config.xml and target android-22.

    <platform name="android">
        <allow-intent href="market:*" />
        <preference name="android-targetSdkVersion" value="22"/> 
    </platform>
    
This example also works with iOS.
