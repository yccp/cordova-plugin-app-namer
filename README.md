# cordova-plugin-app-namer
This project is forked from [blakgeek/cordova-plugin-app-name](https://github.com/blakgeek/cordova-plugin-app-name)

This project only supports cordova-android >= 7.0.0.
If you need cordova-android < 7.0.0, check the original project link above.
 
## How does it work?
It adds an after_prepare hook that changes the value of app_name in strings.xml for Android and updates the "Project Name" and 
"Project Display Name" in the plist for iOS.

## How do I install it?

If you're like me and using [Cordova CLI](http://cordova.apache.org/):
```
cordova plugin add cordova-plugin-app-namer --variable APP_NAME="应用甲"
```

## How do I use it?
Um ... See above :)




