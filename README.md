# Stupid Rip-Offs Made by AI

Games you've definitely played before. Just worse.

## Put it online (one time)

1. On github.com, click **+ → New repository**, name it `stupid-ripoffs`, make it **Public**, click **Create**.
2. Click **uploading an existing file**, drag in everything from this folder, click **Commit changes**.
3. Go to **Settings → Pages**, set Branch to **main**, click **Save**.
4. Wait 1–2 minutes. Your site: `https://YOUR-USERNAME.github.io/stupid-ripoffs/`

## Add a game (2 steps)

**1. Put the game file in the `games` folder.**
   On GitHub: open the `games` folder → **Add file → Upload files** → drop in your game (e.g. `flappy-bord.html`).
   (Game is just code? Copy `TEMPLATE.html`, rename it, paste the code in where it says.)

**2. Add one line to `games.js`.**
   On GitHub: click `games.js` → the ✏️ pencil → copy the Snek line, change the words:

```js
{ title: "Flappy Bord", ripoffOf: "Flappy Bird", file: "flappy-bord.html", emoji: "🐦", description: "Tap to flap. You will die." },
```

   Click **Commit changes**. Done. The card appears on the homepage within a minute.

**Tips**
- `file` must match the file name exactly (capitals count).
- Keep the comma at the end of each line.
- Game made of several files (images, .js)? Upload them all to one folder like `games/flappy-bord/` and use `file: "flappy-bord/index.html"`.
