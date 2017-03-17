# SwiftReadingResources

## Videos
Pour te décomplexer du Swift
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/AzesJrOcFDU/0.jpg)](http://www.youtube.com/watch?v=AzesJrOcFDU)

## Articles
* Map Filter Reduce <https://useyourloaf.com/blog/swift-guide-to-map-filter-reduce/>

* Swift+Json <https://github.com/bwhiteley/JSONShootout>

* Gérer le JSON en Swift en mode bourrin <https://developer.apple.com/swift/blog/?id=37>

* Générer des classes Swift à partir d'un exemple JSON
	* Pour ObjectMapper <http://parse-amol.rhcloud.com/>
	* <https://github.com/ijoshsmith/json2swift>
	* <https://github.com/insanoid/SwiftyJSONAccelerator>

* Mapper un JSON dans une instance de classe <https://github.com/utahiosmac/Marshal>	

# Simple commands to start
## Ionic 2
### Create a project
```
ionic start SearchSchedulesIonic blank --v2
```

### Create a plugin
```
plugman create --name HelloPluginCordovaSwift --plugin_id cordova-plugins-helloswift --plugin_version 0.0.1 --path .
```

### Plugin to make Swift plugin
```
cordova plugin add cordova-plugin-add-swift-support --save
```

### Supercommand
```
cordova plugin rm cordova-plugin-helloplugin && cordova plugin add ../HelloPluginCordova && cordova plugin rm cordova-plugins-helloswift && cordova plugin add ../HelloPluginCordovaSwift && ionic emulate ios --target="iPhone-5s"
```