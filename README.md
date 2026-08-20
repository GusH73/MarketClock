# Market Clock PWA

A lightweight installable Progressive Web App showing one selected exchange's regular trading hours on an analogue clock in the viewer's local time.

## Default
- ASX (Australian Securities Exchange)
- Regular session: 10:00–16:00 Australia/Sydney
- The app converts the exchange session to the device's local time using browser time-zone data.

## Included markets
ASX, NZX, Tokyo, Singapore, Hong Kong, London, Frankfurt/Xetra, NYSE and NASDAQ.

## PWA features
- Installable to the phone Home Screen.
- Launches in standalone mode without normal browser controls.
- Dedicated Market Clock app icon.
- Safe-area support for modern iPhone and Android devices.
- Basic offline support after the first successful visit.
- Remembers the selected market.
- No backend, database, API key, or build step required.

## Install on Android / Chrome
1. Host the files over HTTPS.
2. Open the site in Chrome.
3. Tap the in-app `Add to Home Screen` button when shown, or use Chrome's menu → Install app.
4. Launch Market Clock from the Home Screen.

## Install on iPhone / Safari
1. Host the files over HTTPS.
2. Open the site in Safari.
3. Tap Share.
4. Choose `Add to Home Screen`.
5. Launch Market Clock from the Home Screen.

## Note
Service workers and PWA installation require HTTPS (or localhost for testing). Opening `index.html` directly from your phone's file system will show the page, but will not provide full PWA installation/offline behaviour.

This version models normal weekday cash-market sessions. Exchange holidays and special/half-day sessions are not yet included.
