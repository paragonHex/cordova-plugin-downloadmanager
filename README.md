# cordova-plugin-downloadmanager
A Cordova plugin to download file in system's default download manager

## Supported Platforms

 - Android (SDK >= 11)

 ## Installation

 ```
 cordova plugin add https://github.com/paragonHex/cordova-plugin-downloadmanager
 ```

 ## How to Use

 ```
 //once device is ready
var fail = function (message) {
    alert(message)
}
var success = function (data) {
        console.log("succes");
}
cordova.plugins.DownloadManager.download("Your URL to download", success, fail);
 ```

## Result

![screenshot](./screenshot/downloadplugin.gif)


## Based on
https://github.com/vasani-arpit/cordova-plugin-downloadmanager
