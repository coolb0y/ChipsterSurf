# ChipsterSurf

ChipsterSurf is a [web browser] for Android. Through a customizable interface it offers a premium experience on a range of Android, Chromebooks and Windows 11 devices.


# Downloads


## Release channels
We have three official public release channels linked above and described below. While we strive to produce stable releases, the Fulguris project is a very small operation. Ultimately the community is responsible for doing the testing and validation of releases. All three variants of the app can be installed at the same time on your device. They are effectively three distinct similar apps. You can differenciate them in your launcher from their slightly modified icon design. Which versions you use and how you manage your updates will define your experience with Fulguris. Update often to help catch bugs before they reach too many users. Wait a couple of weeks and check for known issues before updating if you want to have fewer surprises and a more stable experience.

### 🟢 Google Play

Considered the most stable release channel. Optional [Firebase] statistics and crash report.
If you have more than twenty tabs in a session, it will gently remind you to go for the low cost yearly subscription, every time you open a new tab.

### 🟡 Download 

Provides release candidates and stable releases. Optional [Firebase] statistics and crash report.
Unlimited tabs without subscription. From here you get the most up to date versions.

### 🟠 F-Droid

Provides release candidates and stable releases. No [Firebase] statistics and crash report. Unlimited tabs without subscription.
We have no direct control of the release schedule on this channel. If a broken release reaches it, it may take a couple of weeks to fix it.


# Contribute

## Rate
 
If you don't think it is worth yet then just [open an issue](https://github.com/slion/fulguris/issues) instead. 

## Engage

You can engage with us on our forums, on [GitHub](https://github.com/coolb0y/ChipsterSurf)/issues), or any other social media you can track us down to.

## Translate

Please go ahead and translate on [CrowdIn](https://github.com/coolb0y/ChipsterSurf).

## Code
Code contributions are of course welcome, both bug fix and features.
Please understand that code quality, design and architecture are extremely important as the foremost priority of this project is to deliver a premium browsing experience.
We do our best to avoid treating users as beta testers. Therefore if you want to deliver a new feature expect it to take several iterations before it reaches maturity and is ready for production.


# Features
📑Sessions  
📶 Already Manual Proxy enabled at port 20286
🌍 No Popup on first Start
🌍 Address bar  
🚦Vertical tab panel  
🚥Horizontal tab bar  
⚙Tabs management  
🏞Screen orientations  
🔖Bookmarks  
⌚History  
🌗Force dark mode  
🎨Themes for app and pages  
⛔Ad blocker  
🔒Privacy – Incognito mode  
🔎Search & suggestions – Google, Bing, Yahoo, StartPage, DuckDuckGo…  
♿Accessibility  
⌨Keyboard support  
⚡Hardware accelerated  
🖥️ Desktop rendering  
🖥️ Android desktop support – Samsung Dex, EMUI Desktop  
🌐 Languages  
🔧Settings – lots  
📶 Orbot Proxy support and I2P support – Beta

# Permissions

## Automatically granted
* `INTERNET`: necessary to access the internet.
* `ACCESS_NETWORK_STATE`: used by the browser to stop loading resources when network access is lost.
* `INSTALL_SHORTCUT`: used to add shortcuts with the "Add to home screen" option.

## Requested only when needed
* `WRITE_EXTERNAL_STORAGE`: needed to download files and export bookmarks.
* `READ_EXTERNAL_STORAGE`: needed to download files and import bookmarks.
* `ACCESS_FINE_LOCATION`: needed for sites like Google Maps, requires "Location access" option to be enabled (default disabled).
* `RECORD_AUDIO`: needed to support WebRTC, requires "WebRTC Support" option to be enabled (default disabled).
* `CAMERA`: needed to support WebRTC, requires "WebRTC Support" option to be enabled (default disabled).
* `MODIFY_AUDIO_SETTINGS`: needed to support WebRTC, requires "WebRTC Support" option to be enabled (default disabled).

# Tools

Here are some of the tools we use to develop Fulguris:

* [Android Studio]
* [SVG path editor]: Most useful to quickly modify icons
* [Affinity Designer]: Vector graphics

[Discord]: https://discord.com/invite/7M4Ms5dMZE
[Web browser]: https://en.wikipedia.org/wiki/Web_browser
[Firebase]: https://firebase.google.com
[SVG path editor]: https://yqnn.github.io/svg-path-editor/
[Android Studio]: https://developer.android.com/studio
[Affinity Designer]: https://affinity.serif.com/en-us/designer/
To sign apk
```apksigner sign --ks my-release-key.jks --ks-key-alias my-key-alias --out signed.apk Fulguris-v1.9.31-slions-full-fdroid-release-unsigned.apk``` 