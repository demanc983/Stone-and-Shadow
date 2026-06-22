# Stone & Sword — Part 1: The Adventure Begins

A little top‑down adventure game made for two brothers, **Arlo** and **Axel**, set in a pixel‑art version of Rowledge village. It's a single, self‑contained web page — no installer, no downloads, no internet needed once it's loaded. Just open it and play.

It's built to be played on a phone or tablet (with on‑screen buttons), and it works in any modern browser.

## How to play

It's Arlo's birthday. Read the note from Mamma and Pappa, then explore the village to find your present:

- **Read the note** in your bedroom to start the adventure.
- **Follow the five Swedish flags**, one clue at a time — they lead you to the school, the church, The Pub, the shop, and finally the cricket pitch.
- **Get a shovel** (buy one at the Co‑Op or find one in the cricket shed) and **dig up the treasure** where the X appears.
- Keep your eyes peeled for the **coins** Mamma and Pappa dropped around the village!

### Controls (phone / tablet)

- **On‑screen pad** — move around (with diagonals)
- **ACT** — read, open, dig, talk, and pet the cats
- **POWER** — use your amulet (appears once you find it)
- **SWITCH** — swap between Arlo and Axel

You start out controlling **Arlo**, the birthday boy, and Axel follows along. The cats, **Pickles** and **Pebbles**, trot after you too.

## What's in the village

Rowledge has a cricket ground with a pavilion, a caged tennis court and a children's playground; a school with its own fenced playground; St James's Church; The Pub; the Co‑Op shop; a Village Hall that's still under construction; and the edge of magical Alice Holt Forest. Roads ring the green — Fullers Road, School Road, Recreation Road, Rosemary Lane and Church Lane.

## The files

- **`index.html`** — the whole game in one file. This is the main thing you host. It contains all the code, all the artwork (drawn with code, no image files) and all the sound.
- **`icon.png`** — the app icon (the two amulets) used when you add the game to your home screen.
- **`site.webmanifest`** — a tiny settings file that lets the game install as a full‑screen app.
- **`StoneAndSword.tsx`** — a React version of the same game, only needed if you want to embed or test it inside a React project. **You do not need this for GitHub Pages.**
- **`README.md`** / **`DEPLOY.md`** — these notes.

Upload `index.html`, `icon.png` and `site.webmanifest` together to the top level of your repository.

## Running it on your own device

Just open `index.html` in any browser — double‑tap it in the Files app, or drag it into a browser window. That's it.

## Putting it online with GitHub Pages

GitHub Pages gives the game a public web address (a URL) anyone can visit for free. See `DEPLOY.md` for step‑by‑step instructions you can follow entirely from a phone.

The short version:

1. Create a free GitHub account and a new **public** repository.
2. Upload **`index.html`** to the top level of the repository.
3. Turn on **Pages** in the repository's **Settings**, choosing the `main` branch and the root (`/`) folder.
4. Wait a minute, then visit `https://YOUR‑USERNAME.github.io/YOUR‑REPO‑NAME/`.

Because the file is named `index.html` and sits at the root, the game loads automatically at that address.

## A note on updates

When you upload a new version of `index.html`, phones often keep showing the old one from their cache. After updating, do a hard refresh or clear the browser cache (on iOS Safari: Settings → Safari → Clear History and Website Data) so you see the latest version.

## Credits

Made with love for Arlo and Axel. *Part 1 — The Adventure Begins.* To be continued in Alice Holt Forest…
