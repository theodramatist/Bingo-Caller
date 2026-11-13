# Bingo Caller

A caller for 75-ball bingo that runs in the browser on a phone or tablet.

- Calls by hand, at a normal pace, or at speed
- Patterns: regular bingo, hard way, double bingo, corners, letters, blackout, your own shapes, and "any rotation" versions
- Hold for a bingo and check it by tapping the numbers the player reads back
- Winner tally and a record of every game; starting a new game keeps both
- Saves on the device and works with no signal once it has been opened

## Put it on a home screen

Open the page in Safari, tap Share, then Add to Home Screen. On Android, use Chrome's menu and choose Add to Home screen.

Everything is in `index.html`. `sw.js` keeps the saved copy for use without a signal, and `manifest.webmanifest` with the icons makes it a home-screen app.
