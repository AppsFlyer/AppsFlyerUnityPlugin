AppsFlyerUnityPlugin
====================

AppsFlyer Unity Plugin (iOS)

Installation instruction for the AppsFlyer's plugin:
1. Extract the AppsFlyer plugin zip file in your project. 
2. Open /Assets/Editor/PostprocessBuildPlayer and set your AppsFlyer's code and Apple app bundle ID.
 my $APPS_FLYER_KEY = "PLACE YOUR KEY HERE";
 my $APPLE_ID   = "YOUR BUNDLE ID";
3. Build the project for iOS.
4. Open Xcode and add the AdSupport framework to your project:
	4.1 In the project navigator select the root.
	4.2 Chose the unity target
	4.3 Go to the "Build Phase"
	4.4 Expand "Link Binary With Libraries"
	4.5 Click the "+" at the bottom and add the "AdSupport" framework.


Plugin API:
===========
	
Tracking event:
    AppsFlyer.startSession("MyEventName","TheEventValue");

Pelase refer to section 3 at the iOS SDK integration guide for in-app event API documentation.

http://support.appsflyer.com/attachments/token/th1eupyfydtsmpg/?name=AF-iOS-SDK-Integration-Guide-v2.5.1.9.3.pdf

Testing SDK integration:
http://support.appsflyer.com/entries/22904293-Testing-AppsFlyer-iOS-SDK-Integration-



