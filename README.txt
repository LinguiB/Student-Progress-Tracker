Student Progress Tracker — Updated GitHub Pages PWA package

PACKAGE CONTENTS
- index.html: updated application
- manifest.webmanifest: PWA identity and install settings
- sw.js: service worker and updated cache version
- icons/: application icons

UPLOAD TO GITHUB PAGES
1. Download and extract this ZIP.
2. Upload the CONTENTS of the extracted folder to the root of your existing GitHub Pages repository.
3. Keep the icons folder and its contents in the same location.
4. Replace the existing index.html and sw.js with the versions in this package.
5. Keep manifest.webmanifest and the icons in the repository root/folder structure shown here.
6. Commit the changes and wait for GitHub Pages to publish.

IMPORTANT BEFORE UPDATING
- Open the current app and download a full backup first.
- Do not delete or clear the browser's site data. The app stores its data locally.
- Replacing the website files does not transfer data between devices.

ACADEMIC CLASSES AND ARCHIVES
- Classes can be organised by semester number, season (Fall, Spring, or Summer), and academic year.
- Active and archived classes retain their academic classification.
- Use the app's archive and restore controls to move classes between active and archived views.
- Before permanently deleting records, export/download a backup if you want to keep a copy. Permanent deletion cannot be undone from the app.

BACKUPS AND LOCAL DATA
- The app stores its records in the browser on each device. Attachments may be stored in browser IndexedDB.
- Download backups regularly and keep copies somewhere safe (for example, your computer and an external drive).
- Installing the app on another device does not automatically copy records. Use Backup and Restore to transfer data.
- Do not clear browser/site storage unless you have a verified backup.

INSTALL
- Android: Open the HTTPS GitHub Pages URL in Chrome, then choose Install app / Add to Home screen.
- Windows: Open the HTTPS URL in Chrome or Edge and use the install icon/menu.
- iPhone/iPad: Open the HTTPS URL in Safari → Share → Add to Home Screen.

PWA UPDATE NOTE
- The service worker cache version has been increased so existing installations can fetch the updated app shell.
- After deployment, if an installed app still shows the old version, close it completely and reopen it while online. A browser refresh may also be needed.

BILLING / CLOUD NOTE
- This package uses the app's local browser storage and backup/restore workflow. It does not connect the app to Firebase cloud synchronisation or Firebase Storage.
