NC CLIENTS  -  app package
==========================

This folder holds your tracker as a stand-alone app. There are two ways to use it.

---------------------------------------------------------------
OPTION 1: GET A REAL APK FILE (about 10 minutes, free)
---------------------------------------------------------------
GitHub builds the APK for you in the cloud. You do not need Android Studio.

1. Create a free account at github.com and sign in.
2. Tap  +  >  New repository. Name it "nc-clients". Keep it Private. Create it.
3. Tap "uploading an existing file". Upload EVERYTHING from this folder,
   including the hidden ".github" folder, the "www" folder and "android-res".
   (Easiest on a computer: unzip this package, then drag all the files in.)
4. Tap Commit changes. Then open the "Actions" tab.
   "Build APK" starts by itself. If it does not, tap it, then "Run workflow".
5. Wait about 5 to 8 minutes until it shows a green tick.
6. Open that run. Under "Artifacts" tap "NC-Clients-APK" to download a zip.
   Inside is  app-debug.apk.
7. Send app-debug.apk to any Android phone (WhatsApp, email, Drive).
   On the phone: open the file and allow "Install unknown apps" when asked.

What the app does: opens like a normal app with the NC icon, works without
internet, Call and Text open the phone and Messages apps, and Excel / backup
files open the share sheet so you can save them or send them.

---------------------------------------------------------------
OPTION 2: NO APK, JUST INSTALL IT (works on Android and iPhone)
---------------------------------------------------------------
1. Put the "www" folder on any free web host. Easiest: app.netlify.com/drop,
   drag the "www" folder in, and you get a link.
2. Open the link on the phone in Chrome (Android) or Safari (iPhone).
3. Android: menu  >  Install app.   iPhone: Share  >  Add to Home Screen.
It then works like an app, including offline.

---------------------------------------------------------------
IMPORTANT
---------------------------------------------------------------
* Each phone keeps its OWN clients and leads (stored inside the app).
  To move data to another phone: "Save backup file" on the old one, send the
  file, then "Restore from file" on the new one.
* Uninstalling the app or clearing its data erases its clients. Back up first.
* The debug APK is meant for your own phones and team. It is not for the
  Play Store.
* To update the app later: replace www/index.html with the new version and
  commit again. A new APK is built.
