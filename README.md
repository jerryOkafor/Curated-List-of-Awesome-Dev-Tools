# Curated List of Awesome Dev Tools!

## 1. Stetho

Stetho is a sophisticated debug bridge for Android applications. When enabled, developers have access to the Chrome Developer Tools feature natively part of the Chrome desktop browser. Developers can also choose to enable the optional dumpapp tool which offers a powerful command-line interface to application internals. The integration with the Chrome DevTools frontend is implemented using a client/server protocol which the Stetho software provides for your application. Once your application is integrated, simply navigate to chrome://inspect and click "Inspect" to get started!

## 2. Android Search

Adds an 'ad' omnibox command and view source links for the Android SDK.
This very simple extension does two things:

1. Adds an 'ad' command to the Chrome Omnibox. For example, typing 'ad ViewGro' will bring up a list of all class names in the Android SDK matching 'ViewGro'—selecting a list item navigates to the relevant Android SDK Reference URL on developer.android.com.
2. Adds a '(view source)' link next to the SDK class name for class reference pages on developer.android.com. Clicking this link navigates to the relevant Google Code Search results from android.git.kernel.org.

Source code available at the link [Click Here](https://github.com/romannurik/AndroidSDKSearchExtension)

## 3. Android Resource Navigator

Enhanced resource navigation for GitHub hosted Android projects
### Features:
1. Android XML resources viewed on GitHub are processed so that any contained resource identifiers will link directly to the appropriate external file or specific declaration line where appropriate.
2. Quickly open the Android framework styles or themes XML via an always available browser action button.
3. Type 'arn ' followed by a search term into the address bar to find a particular Android framework style or theme. Use the suggestions to navigate directly to the appropriate XML resource definition.
4. Right-click on the page for any drawable resource and select 'Download Drawable' to download a .ZIP file archive conatining the file assets at all pixel densities. For XML resources, the download archive will contain ALL dependent file assets at all pixel densities including the XML.

## 4. Desktop Notification for Android
Receive Android notifications in your browser.
This extension allows you to receive Android notifications in your browser. In order to use this extension you also need to download and install a free app for your Android phone or tablet.

Desktop Notifications on Google Play Check this [Link](https://play.google.com/store/apps/details?id=org.hcilab.projects.notification)
		
After installing the app on the phone, sign into your Google account on both the phone and Chrome to connect the devices.

Compatible with all popular messengers like WhatsApp, Facebook Messenger, Telegram and Hangouts.

## 5. Chuck
Chuck is a simple in-app HTTP inspector for Android OkHttp clients. Chuck intercepts and persists 
all HTTP requests and responses inside your application, and provides a UI for inspecting their content(Request Params and Response Params).

Apps using Chuck will display a notification showing a summary of ongoing HTTP activity. Tapping on the notification launches 
the full Chuck UI. Apps can optionally suppress the notification, and launch the Chuck UI directly from within their own interface. 
HTTP interactions and their contents can be exported via a share intent.

The main Chuck activity is launched in its own task, allowing it to be displayed alongside the host app UI using Android 7.x multi-window support.

For more Information on Chuk, check the Chuck Repository and Documentation on Github [Here](https://github.com/jgilfelt/chuck)

## 6. NetFox
Netfox A lightweight, one line setup, network debugging library that provides a quick look on all executed network requests performed by your iOS or OSX app. It grabs all requests - of course yours, requests from 3rd party libraries (such as AFNetworking, Alamofire or else), UIWebViews, and more

Very useful and handy for network related issues and bugs Implemented in Swift 2.1 - bridged also for Objective-C

NetFox is similar to chuck in functionality, while chuck is for Android Apps, Netfox s for IOS or OSX apps.

For more information on Netfox, checkout the Netfox repository and documentation on Github [Here](https://github.com/kasketis/netfox).
