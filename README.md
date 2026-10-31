# Image to PDF (Android)

Build the APK with no Android Studio:

1. Create a free GitHub account and a new repository (any name, private is fine).
2. Upload everything in this folder to it, including the hidden `.github` folder.
   Easiest: install GitHub Desktop, or run `git init && git add -A && git commit -m init`
   then push to the new repo.
3. Open the repo's Actions tab. The "Build Android APK" run starts by itself (about 4 minutes).
4. Open the finished run and download `image-to-pdf-apk` at the bottom. Unzip it to get `app-debug.apk`.
5. Send the APK to a phone and tap it to install. Allow "Install unknown apps" when asked.

Change the app later: edit `www/index.html`, push, and download the new APK.
