# tracks-plugin

Status: currently in purgatory. The catalog that gets created to play all the tracks uses youtube links. Random links will be unembeddable and wont play. But this only exists for embedded videos playing in local env (e.g. in an extension). Those same dead links will still work if theyre played in the github pages generated page. So a bit of a crossroads on how to proceed. Couldn't figure out how to convince youtube to actually play the videos that are failing inside the plugin.

## Links for Setting up Native Messaging

### Setting up native manifest (files inside the Mozilla folder)
These files need to be moved to another local folder for native messaging to work. See the setup file for more.
https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Native_manifests

### Links I used to setup NativeMessaging (one way comms)
https://github.com/mdn/webextensions-examples/tree/master/native-messaging
https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/runtime/sendNativeMessage
https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Native_messaging

### Connect Native (two way comms)
https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/runtime/connectNative

### Related but didnt use really
https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/permissions
https://blog.mozilla.org/addons/2016/06/09/webextensions-for-firefox-49/

## Example extensions using native messaging features
https://github.com/mdn/webextensions-examples/tree/master/export-helpers
https://github.com/darktrojan/openwith/blob/master/webextension/manifest.json
https://github.com/darktrojan/openwith/blob/f80cb8e61dfe79079e69dab206af5e55bd0e250d/webextension/native/open_with_mac.py

## All Mozilla Example Extensions with list of API's used by them
https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Examples