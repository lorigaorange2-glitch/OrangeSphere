# OrangeSphere — installable web app (PWA)

## What this version is
This is a Progressive Web App (PWA) version of the OrangeSphere prototype. Once hosted on an HTTPS website, supported Android browsers can install it to the home screen and open it in an app-like window. The service worker caches the app shell for basic offline reopening.

## Install on Android
1. Publish the contents of this folder to a static HTTPS host (for example, a static site host).
2. Open the published HTTPS URL in Chrome on Android.
3. Tap **Install app** if the button appears, or Chrome menu (⋮) → **Install app** / **Add to Home screen**.
4. Confirm. OrangeSphere should appear as an icon on your home screen.

## Important
- This is not an APK and is not listed on Google Play.
- The browser generally will not install a PWA securely from a local `file://` URL. It must be hosted on HTTPS or localhost.
- The current tutor is a guided template, not live AI. PDF entries store filenames only. The community is local-only.
- Notes and progress are stored in browser local storage and do not sync across devices.
- The app shell can reopen offline after first successful load, but features needing online services are not implemented.
