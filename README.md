# Pehli Varshganth · Naman & Dhruti

Bhai & Bhabhi ni pehli wedding anniversary mate website.

## 1. Date & music set karo (jaruri)
`index.html` kholo, niche `CONFIG` shodho:

```js
const CONFIG = {
  groom: "Naman",
  bride: "Dhruti",
  from:  "Drashti",
  weddingDate: "2025-11-30",   // lagna ni date (YYYY-MM-DD)
  music: "media/song.mp3"      // <- tamaru gamtu song media folder ma "song.mp3" naame muko
};
```
Song na muko to music button ane "vinyl record" vali screen aapo-aap chhupai jase. Song mukso to record par photo sathe gaanu vagse.

## 2. GitHub Pages par upload
1. github.com par login -> **New repository** -> naam: `Pehli-Varshganth` -> **Public** -> Create.
2. **Add file -> Upload files** -> aa folder ni badhi files (index.html, images, media, README.md) drag karo -> **Commit changes**.
3. **Settings -> Pages** -> Source: *Deploy from a branch* -> Branch: `main` / `(root)` -> **Save**.
4. 1-2 minute pachhi link aavse: `https://<your-username>.github.io/Pehli-Varshganth/`
