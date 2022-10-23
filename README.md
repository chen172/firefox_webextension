# Description
block bing.com AI

# Usage

## Development
1. In firefox address bar, go to ```about:debugging#/runtime/this-firefox```, click the Load Temporary Add-on button, then select any file in your extension's directory.
2. In firefox address bar, go to ```about:addons```, click on the extension, and select the Allow radio button for Run in Private Windows.
* Note: for more info, see [installing](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension#installing)

## Build to XPI from source
for permanent use it, you need to package and sign the extension as XPI file:

1. install web-ext by [npm](https://github.com/mozilla/web-ext#global-command) or [source](https://github.com/mozilla/web-ext#installation-from-source)
2. cd firefox_webextension
3. get your api-key and apt-secret from https://addons.mozilla.org/developers/addon/api/key/
4. web-ext sign --api-key=$AMO_JWT_ISSUER --api-secret=$AMO_JWT_SECRET
5. after run the above command, you'll receive an email contains the Add-on link, click it to download the Add-on.

# Version
Mozilla Firefox (106.0.1)

# ref
https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension
https://extensionworkshop.com/documentation/publish/signing-and-distribution-overview/
https://extensionworkshop.com/documentation/develop/getting-started-with-web-ext/
