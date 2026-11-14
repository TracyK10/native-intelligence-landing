# Native Intelligence -- landing page

The public landing page for [Native Intelligence](../native-intelligence-app), hosted on
GitHub Pages. One static page: what the app does, the privacy notice, a download link for
the signed APK, and feedback/beta sign-up links.

This repo is separate from and public, unlike the app's source repo, which stays private
because its test samples come from real (anonymized) MoMo messages.

## Updating the APK

When a new signed release APK is ready:

1. Copy the new `.apk` into this repo, named `NativeIntelligence-vX.X.apk`.
2. Update the download link in `index.html` to match.
3. Remove the old APK file.
4. Commit and push -- GitHub Pages redeploys automatically from `main`.

## Updating the privacy notice

Keep this page's privacy notice section in sync with the one inside the app
(`ui/screens/PrivacyNoticeScreen.kt` in the app repo). They should always say the same thing.

## Local preview

It's a single static HTML file with no build step -- just open `index.html` in a browser.
