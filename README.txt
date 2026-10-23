REVISION HQ - YEAR 9 IPHONE APP

FILES
- index.html: the app
- manifest.json: home-screen app settings
- sw.js: basic service worker

WHAT IT DOES
- 45-minute daily revision structure rotating Maths, English, Science, History and Geography
- task checkboxes, daily completion percentage, streak and test countdown
- editable test date and reminder time
- saves progress in the same browser/device using local storage

IMPORTANT LIMITATION
This is a small installable web app, not an App Store app. A reliable 5 pm notification while the app is fully closed needs a secure hosted site plus a push-notification service. This basic version can ask for browser notification permission and check the time while the app is open, but cannot guarantee closed-app reminders. You can use an Apple Calendar alert as a reliable backup.

HOW TO PUT IT ON YOUR IPHONE
1. Host these files on a secure HTTPS static website (for example, GitHub Pages). Keep index.html, manifest.json and sw.js together in the published root.
2. Open the HTTPS website in Safari on your iPhone.
3. Tap Share (square with arrow) > Add to Home Screen.
4. Name it Revision HQ and tap Add.
5. Open the new home-screen icon, set your test date when you know it, and tap Enable reminder.
6. Use the same home-screen app each day so its saved progress remains in the same browser storage.

If hosting is too fiddly, you can open index.html to preview it, but a local file cannot be installed as a full web app and background reminders will not work.
