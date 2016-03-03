# cordova-plugin-add-swift-support

This [Cordova plugin](https://www.npmjs.com/package/cordova-plugin-add-swift-support) adds the Swift support to your iOS plugins.


## Installation

From your project,

* using the cordova CLI :

 `cordova plugin add cordova-plugin-add-swift-support`

* editing the `config.xml` file of your project :

 `<plugin name="cordova-plugin-add-swift-support" spec="~1.0.1" />`

If needed, add a Bridging-Header file in your plugin in order to import frameworks.

:warning::warning::warning: Be sure to add this plugin after all other. If you edit the config.xml file add it in the last row of your plugins list. As an exemple, you can have a look [here](https://github.com/akofman/cordova-plugin-dbmeter).

## License

Apache-2.0 © [Alexis Kofman](http://twitter.com/alexiskofman)
