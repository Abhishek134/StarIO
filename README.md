This is a starter template for Ionic Star printer 

## How to use this template

Notice in the config.xml the plugins section.

    `<plugin name="star-printer-plugin" spec="https://github.com/InteractiveObject/StarIOPlugin.git" />`

The cordova commands below will each download and install this plugin. 

`cordova prepare ios`  //This sets up the ios environment
`cordova platform add ios` //This calls cordova prepare 

To reset or reinstall the plugin run:
`cordova platform rm ios` //This removes the platform, however does not remove the plugin that is downloaded.
`cordova state reset`  //This removes the platform and removes the plugin



