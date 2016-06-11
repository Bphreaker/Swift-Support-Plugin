# cordova-plugin-add-swift-support

This [Cordova plugin](https://www.npmjs.com/package/cordova-plugin-add-swift-support) adds the Swift support to your iOS project.

## Installation

You can add this plugin directly to your project :

`cordova plugin add cordova-plugin-add-swift-support --save`

Or add it as a dependency into your own plugin :

`<dependency id="cordova-plugin-add-swift-support" version="1.3.1"/>`

If needed, add a prefixed Bridging-Header file in your plugin in order to import frameworks (MyPlugin-Bridging-Header.h for instance).
As an example you can have a look at this [plugin](https://github.com/akofman/cordova-plugin-permissionScope).

If the `cordova-plugin-add-swift-support` plugin is already installed to your project, then you can add your own Swift plugin as usual, its prefixed Bridging-Header will be automatically found and merged.

## License

Apache-2.0 © [Alexis Kofman](http://twitter.com/alexiskofman)
