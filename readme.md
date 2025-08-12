# Welcome to Mhatxotic Design live stream…

## About…
This repository contains a webpage with our embedded [kick.com](https://kick.com/mhatxotic) live stream along with our [twitch.tv](https://twitch.tv/mhat) chat. The reason for this existing is because Twitch has an obnoxious amount of commercials (unless you know how to block them which you can) whilst Kick does not show commercials at all so why not use both? You only need a Twitch account to chat and you do not need Kick account to watch. Also, the problem with Kick chat is you need a remote server to be able to read the chat so interactive streams cannot feasibly exist and security there will be lax.

## Issues…
When you first load the Twitch chat on mobile, you can get an obnoxious cookie disclaimer fill the whole screen and the `reject` button is hidden from view due the enormous pointless wall of text. You can either…

* Use a content blocker to suppress the disclaimer.
* Click the `customise` button if visible and uncheck all the cookies there manually.
* Zoom out the page with the zoom control so you can gain access to the appropriate button.
* Save the page as an app to the home screen and you will see all the buttons that way too.
* Hide the browser toolbar and gain access to the button.

Another issue on both desktop and mobile is that when you refresh the page, the Kick stream can sometimes say that `This embed seems to be misconfigured`. This is an issue with the embedded player. A workaround for this is to either…

* Go into the address bar and press return on the address text.
* Close the tab and go back to the page.
* Quit the browser app and go back to the page.
* Clear the cache for the website.

## Blocking Twitch Commercials…
If you would rather just learn how to block Twitch commercials then find out how below depending on the device you are using.

### Windows, MacOS and Linux…
The best option for blocking Twitch commercials is to…

* Use a Gecko based browser which has the greatest capabilities for user add-ons such as…
  - [Firefox](https://firefox.com).
  - [LibreWolf](https://librewolf.net).
  - [WaterFox](https://waterfox.net).
* **Option A:** Install the [UBlock Origin](https://addons.mozilla.org/firefox/addon/ublock-origin/) extension and reference the [vaft](https://github.com/pixeltris/TwitchAdSolutions/raw/refs/heads/master/vaft/vaft-ublock-origin.js) user script in its advanced settings by following this [guide](https://github.com/pixeltris/TwitchAdSolutions?tab=readme-ov-file#applying-a-script-ublock-origin) from [PixelTris](https://github.com/pixeltris).
* **Option B:** Install the [TamperMonkey](https://addons.mozilla.org/en-GB/firefox/addon/tampermonkey/) extension with the  [vaft](https://github.com/pixeltris/TwitchAdSolutions/raw/refs/heads/master/vaft/vaft.user.js) user script from [PixelTris](https://github.com/pixeltris) _or_ the [AdGuard Extra user script](https://userscripts.adtidy.org/release/adguard-extra/1.0/adguard-extra.user.js) from the [AdGuard Extra repository](https://github.com/AdguardTeam/AdGuardExtra).
* **Option C:** Install the [AdGuard Extra Firefox add-on](https://agrd.io/adguard_extra_firefox_release) from the [AdGuard Extra repository](https://github.com/AdguardTeam/AdGuardExtra). This add-on is safe to use alongside UBlock Origin without any of the aforementioned user scripts configured.

### iOS and MacOS Safari…
Install the free [Userscripts](https://apps.apple.com/app/id1463298887) app for MacOS and iOS and use the same [vaft](https://github.com/pixeltris/TwitchAdSolutions/raw/refs/heads/master/vaft/vaft.user.js) script with the app _or_ the [AdGuard Extra user script](https://userscripts.adtidy.org/release/adguard-extra/1.0/adguard-extra.user.js) from the [AdGuard Extra repository](https://github.com/AdguardTeam/AdGuardExtra). This solution does not always work unfortunately.
