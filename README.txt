CHRISTMAS v1.2.2 (2026-11-18)

A shared list of gift ideas. Four cards: Raul, Amparo, Mateo and Mario. Open a card, tap Add an idea, and fill in the name, seller and price. Paste a web address into Link and the app looks for a picture, and fills in the name and shop if they are empty. Tap the circle when something has been bought. Tap an item to edit or delete it.

Files for a NEW repository (root): index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png

1. GitHub: create a new public repository called Christmas (same account as the others).
2. Add file > Upload files, drop the five files above, commit.
3. Settings > Pages > Deploy from a branch > main, folder / (root), Save.
4. Firebase console > Authentication > Settings > Authorised domains: annoyingkay.github.io is already there for the other apps, so nothing to add.
5. Publish the updated firestore.rules from the Libraries repository (Firebase console > Firestore Database > Rules > paste the whole file > Publish). Until you do, this app will say the account is not on the list.
6. Open https://annoyingkay.github.io/Christmas/ and reload twice. Add it to the home screen on both phones.

Sign in with the same two Google accounts as Musicbox and SavePoint.

Notes
- Choosing a picture: after you paste a link, a row of pictures from that page appears. Tap one to pick it, or tap No picture. You can also paste a picture link of your own (on a phone, press and hold the picture on the shop page and choose Copy image address). A link that already ends in .jpg, .png or .webp is used as the picture directly.
- Pictures come from a free preview service called Microlink (api.microlink.io). The link you paste is sent to it, nothing else. The free allowance is about 50 lookups a day, which is plenty for a family list. Some shops block previews; the item still saves, just without a picture. Only the picture's web address is stored, so a shop can later remove it.
- Only the current year's ideas show. Last year's stay in the database and are included in Export backup.
- Both accounts see every list. If you want a list to hide ideas from its owner (for surprises), that can be added.
- Rules: the Christmas block is in the master firestore.rules in the Libraries repository. Do not keep a copy in this repository.
