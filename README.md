This is a starter template for Ionic Star printer 

Clone repository
`git clone xxxxx`

Install npms
`npm install`

Add platform
`ionic cordova platform add ios` 

Build
`ionic build ios`

Notice in the package.json the plugins section.

`"cordova-stario-plugin": "git+https://github.com/InteractiveObject/StarIOPlugin.git",`

`"cordova": {
        "plugins": {
            "cordova-plugin-console": {},
            "cordova-plugin-device": {},
            "cordova-plugin-splashscreen": {},
            "cordova-plugin-statusbar": {},
            "cordova-plugin-whitelist": {},
            "ionic-plugin-keyboard": {},
            "cordova-stario-plugin": {}
        },
        "platforms": [
            "ios"
        ]
    }`

The cordova commands below will each download and install this plugin. 

`cordova prepare ios`  //This sets up the ios environment
`cordova platform add ios` //This calls cordova prepare 

To reset or reinstall the plugin run:
`cordova platform rm ios` //This removes the platform, however does not remove the plugin that is downloaded.
`ionic state reset`  //This removes the platform and removes the plugin



