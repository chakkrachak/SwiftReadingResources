# SwiftReadingResources

## Videos
### Pour te décomplexer du Swift
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

* Xcode things
	* <https://robots.thoughtbot.com/building-ios-interfaces-custom-button>
	* <https://robots.thoughtbot.com/building-ios-interfaces-swift-primer>
	* <https://robots.thoughtbot.com/building-ios-interfaces-views>
	* <https://www.appcoda.com/custom-search-bar-tutorial/>

* Clean Swift
	* <http://clean-swift.com/clean-swift-ios-architecture/>
	* <https://cocoacasts.com/swift-and-model-view-viewmodel-in-practice/> 	
* Cocoapods
	* <https://www.raywenderlich.com/97014/use-cocoapods-with-swift> 

* Unit tests
	* <https://x-team.com/blog/how-to-get-started-with-ios-unit-tests-in-swift/> 

# Material design things
## Colors
<https://www.materialpalette.com/cyan/pink>

## UIs
<https://material.uplabs.com/>

# Simple commands to start
## Ionic 2
### Create a project
```
ionic start SearchSchedulesIonic blank
```
### Launch on emulator with livereload
```
ionic cordova emulate android --livereload
```

### Create a plugin
<https://cordova.apache.org/docs/en/latest/guide/platforms/ios/plugin.html>

<http://moduscreate.com/plugin-authoring-cordova-6-ios-android/>
```
plugman create --name HelloPluginCordovaSwift --plugin_id cordova-plugins-helloswift --plugin_version 0.0.1 --path .
```

### Plugin to make Swift plugin
<http://moduscreate.com/writing-a-cordova-plugin-in-swift-3-for-ios/>

<https://github.com/bitjson/cordova-plugin-swift-support>

```
cordova plugin add cordova-plugin-add-swift-support --save
```

### Supercommand
```
cordova plugin rm cordova-plugin-helloplugin && cordova plugin add ../HelloPluginCordova && cordova plugin rm cordova-plugins-helloswift && cordova plugin add ../HelloPluginCordovaSwift && ionic emulate ios --target="iPhone-5s"

```

### Big steps for a Cordova Swift plugin
<http://moduscreate.com/writing-a-cordova-plugin-in-swift-for-ios/>

* Create project {project}
* Create plugin {plugin}
	* Add cordova-plugin-add-swift-support dependancy in plugin
	* Add {plugin}.swift and reference it in plugin.xml
	* Add functions in {plugin}.swift and use it in {plugin}.js
	* If you want to use more code, include it and reference it in plugin.xml
	* Do a Bridge-header and reference it in plugin.xml
* Add {plugin} in {project}
* Build  

### Ionic 2 things
<https://blog.thoughtram.io/angular/2016/10/13/two-way-data-binding-in-angular-2.html>

<https://blog.thoughtram.io/angular/2016/02/22/angular-2-change-detection-explained.html>
