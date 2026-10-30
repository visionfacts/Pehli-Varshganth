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
- `media/song.mp3` = "Pehle Bhi Main" (aakhi website ma background ma, loop)
- `media/reel-song.mp3` = "Tum Ho Toh" (fakt reel page par, video sathe loop; reel vakhte background song pause)
- `reelSongStart` = reel song ketla second thi sharu thay
- `readSeconds` = vaanchva vala page par ketla second pachhi "Continue" khule

Darek page puru thay pachhi j aagal javay: badha photo jovay, candle, scratch, saat phera, slider, puri reel, badha games.

## 2. GitHub Pages par upload
1. github.com par login -> **New repository** -> naam: `Pehli-Varshganth` -> **Public** -> Create.
2. **Add file -> Upload files** -> aa folder ni badhi files (index.html, images, media, README.md) drag karo -> **Commit changes**.
3. **Settings -> Pages** -> Source: *Deploy from a branch* -> Branch: `main` / `(root)` -> **Save**.
4. 1-2 minute pachhi link aavse: `https://<your-username>.github.io/Pehli-Varshganth/`
