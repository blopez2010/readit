# ReadIt

## Certificate configuration

For development *ONLY* set `verifyUpdateCodeSignature` to `false` when certificate is temporary, otherwise `true`.

## Build distribution file

* For Mac *ONLY* run: `npm run mac`
* For Windows *ONLY* run: `npm run win`
* For Linux *ONLY* run: `npm run lin`
* For all platforms run: `npm run build`

## Electron log locations

Package https://www.npmjs.com/package/electron-log

* on Linux: `~/.config/<app name>/log.log`
* on OS X: `~/Library/Logs/<app name>/log.log`
* on Windows: `%USERPROFILE%\AppData\Roaming\<app name>\log.log`

## Publishing App

`GH_TOKEN=private-token electron-builder build -m -p 'onTagOrDraft'`