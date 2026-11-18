CHRISTMAS v1.0.1 (2026-11-18)

A shared list of gift ideas. Four cards: Raul, Amparo, Mateo and Mario. Open a card, tap Add an idea, and fill in the name, seller and price. Tap the circle when something has been bought. Tap an item to edit or delete it.

Files for a NEW repository (root): index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png

1. GitHub: create a new public repository called Christmas (same account as the others).
2. Add file > Upload files, drop the five files above, commit.
3. Settings > Pages > Deploy from a branch > main, folder / (root), Save.
4. Firebase console > Authentication > Settings > Authorised domains: annoyingkay.github.io is already there for the other apps, so nothing to add.
5. Publish the updated firestore.rules from the Libraries repository (Firebase console > Firestore Database > Rules > paste the whole file > Publish). Until you do, this app will say the account is not on the list.
6. Open https://annoyingkay.github.io/Christmas/ and reload twice. Add it to the home screen on both phones.

Sign in with the same two Google accounts as Musicbox and SavePoint.

Notes
- Only the current year's ideas show. Last year's stay in the database and are included in Export backup.
- Both accounts see every list. If you want a list to hide ideas from its owner (for surprises), that can be added.
- Rules: the Christmas block is in the master firestore.rules in the Libraries repository. Do not keep a copy in this repository.
