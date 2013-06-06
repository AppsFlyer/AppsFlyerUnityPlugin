AppsFlyerUnityPlugin
====================

AppsFlyer Unity Plugin (iOS)

Installation instruction for the AppsFlyer's plugin:
<br/>
1. Extract the AppsFlyer plugin zip file in your project. 
<br/>
2. Open /Assets/Editor/PostprocessBuildPlayer and set your AppsFlyer's code and Apple app bundle ID.
<br/>
 my $APPS_FLYER_KEY = "PLACE YOUR KEY HERE";
 <br/>
 my $APPLE_ID   = "YOUR BUNDLE ID";
 <br/>
3. Build the project for iOS.<br/>
4. Open Xcode and add the AdSupport framework to your project:<br/>
	4.1 In the project navigator select the root.<br/>
	4.2 Chose the unity target<br/>
	4.3 Go to the "Build Phase"<br/>
	4.4 Expand "Link Binary With Libraries"<br/>
	4.5 Click the "+" at the bottom and add the "AdSupport" framework.<br/>
<br/>
<br/>
Plugin API:<br/>
<br/>	
Tracking event:<br/>
    AppsFlyer.startSession("MyEventName","TheEventValue");<br/>
<br/>
Pelase refer to section 3 at the iOS SDK integration guide for in-app event API documentation.<br/>
<br/>
http://support.appsflyer.com/attachments/token/th1eupyfydtsmpg/?name=AF-iOS-SDK-Integration-Guide-v2.5.1.9.3.pdf<br/>
<br/>
Testing SDK integration:<br/>
http://support.appsflyer.com/entries/22904293-Testing-AppsFlyer-iOS-SDK-Integration-



