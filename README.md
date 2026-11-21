# Secure Vault

An encrypted notebook for passwords, PINs, cards and bank details. Works offline and installs on your phone.
Your data never leaves the device: it is encrypted (AES-256-GCM, key from PBKDF2 with your master password)
and stored only in this browser/app. Do NOT put your own data or backups into this repository.

## Put the app on GitHub Pages (the app only, no data)
1. Create a new public repository, for example `vault`.
2. Upload every file in this folder (index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png).
3. Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. After a minute the app is live at `https://YOUR-USERNAME.github.io/vault/`.

## Install on your phone
- Android (Chrome): open the link, menu > "Install app".
- iPhone (Safari): open the link, Share > "Add to Home Screen". Always open it from the home-screen icon.

## First use
Open the app, create a master password (8+ characters, a long phrase is best). There is NO recovery if you forget it.
Settings > Export encrypted backup regularly and keep the file in your own cloud drive or send it to yourself.
Phones can clear website data, so the backup is your safety net.
