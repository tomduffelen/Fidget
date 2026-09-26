SIX-SIDED FIDGET: installable app

1. HOST IT ON GITHUB PAGES (free)
   a. Make a free account at github.com, then click New repository.
      Name it e.g. "fidget", set it to Public, and create it.
   b. Click "uploading an existing file" and drag in EVERYTHING inside this
      folder (index.html, manifest.webmanifest, sw.js, the icons folder, this file).
      index.html must be at the top level, not inside another folder. Commit.
   c. Settings > Pages > Source: "Deploy from a branch" > Branch: main, folder: / (root) > Save.
   d. After a minute or two it's live at https://YOUR-USERNAME.github.io/fidget/
   (Netlify Drop at https://app.netlify.com/drop also works: just drag the folder.)

2. INSTALL IT
   iPhone/iPad: open the link in Safari > Share > Add to Home Screen.
   Android: open in Chrome > menu > Install app (or Add to Home screen).
   It opens full screen with no browser bars, and works offline after the first visit.

3. UPDATING IT LATER
   Upload the new files over the old ones on GitHub. Then open the app and tap
   the refresh button (the circular arrow, top right). The app checks for the
   new version when it's online.

4. LOCK IT FOR A CHILD
   In the app, tap "Child lock". The controls hide, the back button stops working,
   and a padlock appears bottom-right. To unlock: hold the padlock for 3 seconds,
   then answer the times-table question.

   No web page or web app is allowed to stop someone leaving it (swiping home,
   switching apps). For a proper lock, also turn on the phone's own feature:
   - iPhone/iPad: Settings > Accessibility > Guided Access > On.
     Open the app, triple-click the side (or Home) button, tap Start.
     Triple-click again and enter your passcode to leave.
   - Android: Settings > Security > App pinning (or "Screen pinning") > On.
     Open the app, go to Recent apps, tap the app icon > Pin.
     Hold Back + Overview (or swipe up and hold) and enter your PIN to leave.
