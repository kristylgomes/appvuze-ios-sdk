# appvuze-ios-sdk
appVuze iOS screensharing SDK

1.  Copy UXCapture.framework into your project directory
2.  From XCode menu, choose File -> Add files to and locate UXCapture.framework in your project hierarchy and click "Add"
3.  Open your target build settings -> Build Phases tab. Expand “Link Binary with Libraries” and add libc++.tbd (or libc++.dylib on Xcode     6.x and older)
4.  Open your application’s plist file and add the following key: 
5.  App Transport Security Settings -> Allow Arbitrary Loads-> YES
6.  Next, add the following plist key so that your application can be launched with appVuze app: 
    URL types -> Item 0 -> URL identifier -> appVuze 
    URL types -> Item 0 -> URL Schemes -> Item 0 -> appvuzecom.appvuze.ios.testapp1 (or testapp2 or testapp3)
7.  Once you have finished downloading our SDK, please email us at maksim@appvuze.com to get the final step
    
    NOTE: Test URL schemes are intended for internal and private testing purposes only. If you would like to publish your application with appVuze SDK on the Apple App Store or enterprise app store for wide distribution, please contact us. You will need to provide us with your application bundle identifier, launch icon, and display name and we will supply a unique URL scheme to launch your application
