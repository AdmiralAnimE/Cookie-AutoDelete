[![Build Status](https://travis-ci.org/mrdokenny/Cookie-AutoDelete.svg?branch=master)](https://travis-ci.org/mrdokenny/Cookie-AutoDelete)
[![Coverage Status](https://coveralls.io/repos/github/mrdokenny/Cookie-AutoDelete/badge.svg?branch=master)](https://coveralls.io/github/mrdokenny/Cookie-AutoDelete?branch=master)
# Cookie-AutoDelete
Control your cookies! This extension is inspired by Self Destructing Cookies. When a tab closes, any cookies not being used are automatically deleted. Prevent tracking by other cookies and add only the ones you trust. Easily import and export your Cookie Whitelist.

## Main Features
- Auto Deletes Cookies from Closed Tabs
- WhiteList Support for Sites you want to keep Cookies
- Easily Export/Import your Whitelist
- Clear All Cookies for a Domain
- Support for Container Tabs (Firefox 53+ Only)

### Usage
1. Add the sites you want to keep cookies in the whitelist
2. Enable "Active Mode" in the popup or settings
3. Watch those unused cookies disappear :)

## Other Versions
[Chrome](https://chrome.google.com/webstore/detail/cookie-autodelete/fhcgjolkccmbidfldomjliifgaodjagh)

[Firefox](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete/)

## Internationalization (i18n)

Translate Cookie AutoDelete in your language or help fix a translation!

1. Copy and paste the "/extension/_locales/en" folder.
2. Rename the newly copied folder to the language codes found [here](https://developer.chrome.com/webstore/i18n?csw=1#localeTable)
3. Open the manifest.json in your newly created folder and start translating the "message" JSON properties. The description should be left alone as a reference. Also any word with '$' surrounding it should be left alone as they are placeholders.
4. Test the translation by building it. Fix any UI glitches by if possible using a shorter translation.
5. Make a Pull Request and you're done!.
6. Watch for changes in the "/extension/_locales/en/messages.json" file for future updates or if the updates somehow got lost use a [diff tool](https://www.diffchecker.com/diff).

## Build Intructions

1. Run `npm install`
2. Run `npm run-script build`
3. The build files should be in a new folder called `/builds`