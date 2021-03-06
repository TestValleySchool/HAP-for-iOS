# Home Access Plus+ for iOS

Home Access Plus+ (HAP) for iOS provides a native app to connect your Apple device to your institutions [Home Access Plus+](https://hap.codeplex.com) server. You can then browse, upload and download files easily to and from your iOS device to your institution network file drives. A [demo video](https://www.youtube.com/watch?v=cpr7Ar-a5MA) and [screenshots](https://goo.gl/photos/6Ptp4J1woojWuUik9) are available to view of the app in action (version 0.5.0).

## Requirements
To be able to use this app, you will need to have the following:
* iOS 9 device
* [Home Access Plus+](https://hap.codeplex.com) set up and running for your institution (bug your network managers to get this set up&hellip; it's free)

## Frequently Asked Questions
Before asking for help or reporting a bug, please read through the [Frequently Asked Questions](FAQ.md) to see if the problem can be resolved.

## Contributing
Thanks for your interest in contributing to this project. You can contribute or report issues in the following ways:
* [Sign up for beta testing](http://www.edugeek.net/forums/home-access-plus/164699-home-access-plus-ios-app-request-testers.html) to explore and test the app
* [Report a bug](http://issuetemplate.com/#/stuajnht/HAP-for-iOS/bug) if something isn't working as you expect it to
* [Suggest an improvement](http://issuetemplate.com/#/stuajnht/HAP-for-iOS/request) for something that you'd like to see

## License Terms
Home Access Plus+ for iOS is publised under the GNU GPL v3 License, see the [LICENSE](LICENSE.md) file for more information.

The name "Home Access Plus+" and all server side code are copyright Nick Brown ([nb development](https://nbdev.uk/projects/hap.aspx))

### Cocoapods
This project uses Cocoapods. Their project source code pages and licenses can be found below:
* [Alamofire](https://github.com/Alamofire/Alamofire/)
* [ChameleonFramework](https://github.com/ViccAlexander/Chameleon)
* [Font Awesome Swift](https://github.com/Vaberer/Font-Awesome-Swift)
* [Locksmith](https://github.com/matthewpalmer/Locksmith)
* [MBProgressHUD](https://github.com/jdg/MBProgressHUD)
* [PermissionScope](https://github.com/nickoneill/PermissionScope)
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON)
* [XCGLogger](https://github.com/DaveWoodCom/XCGLogger)

### Other Projects
The following projects and source code are included in HAP+ for iOS. Their licenses project pages can be found below:
* [Reach](https://github.com/Isuru-Nanayakkara/Reach)

## To-Do List
The following features are planned for the Home Access Plus+ iOS app, along with their expected releases (which can change).

### 0.7.0
* Auto re-login for devices that are in 'personal' or 'single' mode
* Logout button for apps in any mode, to allow other users to log in (devices in 'single mode' need a domain admin to provide credentials first)
* Use the timetable plugin for HAP+ to get the times of lessons, and log the user out if the device is in 'shared' mode and the lesson has finished
* A settings menu of some sort (either in-app or the main settings app)
* Use the document picker control to access files from some apps which don't allow the file to be copied to the app
* Update additional supported file icons
* Update icon so that the ‘house’ isn’t as close to the bottom corner

### 0.8.0
* Swipe table item right to select it or choose cut / copy functions, and paste into new folder
* Disable writing files and folders if the user does not have the permission to, by disabling items in the upload popover