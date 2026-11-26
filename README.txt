NS Field Converter – installable iPhone/Android app
====================================================

Files (upload all of them, in one folder, keeping these names):
  index.html  manifest.webmanifest  sw.js  icon-180.png  icon-192.png  icon-512.png

This package does NOT contain the NS778302 grid (it is licensed). After installing,
load NS778302.GSB once from the phone (section "ATS77 grid file"); it is stored on
that phone only. Everything except ATS77 <-> NAD83 works without it.

Host on GitHub Pages (free)
 1. Sign in at github.com (create a free account if needed).
 2. New repository -> name it e.g. ns-converter -> Public -> Create.
 3. "uploading an existing file" -> drag in the 6 files above -> Commit changes.
 4. Settings -> Pages -> Source: Deploy from a branch -> Branch: main, folder / (root) -> Save.
 5. After a minute the site is at https://YOUR-NAME.github.io/ns-converter/

Install on the iPhone
 1. Open that address in Safari (it must be Safari).
 2. Share button -> Add to Home Screen -> Add.
 3. Open it from the home screen once while you have signal, so it saves itself for offline use.
 4. Put NS778302.GSB in the Files app (tap the .zip to unzip it), then in the app use
    "ATS77 grid file" -> choose NS778302.GSB. It confirms "Saved on this device".
 5. Test: turn on Airplane Mode and open the app – it should work fully.

Updating later: replace index.html in the repository and change VERSION in sw.js
(e.g. nsfc-v2); the phone picks up the new version the next time it opens with signal.
Important: load the grid INSIDE the home-screen app (not in a Safari tab) – on iPhone they keep
separate storage. The grid section says whether you are in the "home-screen app" or a "browser tab".
Note: iPhone may clear a home-screen app's saved data if it goes unused for many weeks;
if the grid ever shows "Not loaded", load the .GSB file again.
