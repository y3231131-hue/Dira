# Flat Manager: setup

1. firebase.google.com > Add project (free). 
2. Build > Authentication > Get started > enable **Anonymous**.
3. Build > Firestore Database > Create database. Then Rules tab: paste firestore.rules and Publish.
4. (Done) Firebase settings are already filled in index.html.
5. Host it: install Node, then `npm i -g firebase-tools`, `firebase login`, `firebase init hosting` (public folder = this folder, single-page = No), `firebase deploy`. You get https://YOURPROJECT.web.app
6. APK: go to pwabuilder.com, paste that address, Package for stores > Android, download, install the APK (allow "unknown apps").
7. First launch asks for a flat code (8+ letters/numbers). Everyone enters the same one. Then add the people in the People tab.
