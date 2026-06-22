# Putting Stone & Sword online with GitHub Pages (from a phone)

This walks you through publishing the game for free, doing everything from **Safari on an iPhone or iPad**. It takes about ten minutes the first time.

You'll upload these files (all to the **top level** of the repository):

- **`index.html`** — the game itself (required)
- **`icon.png`** — the home‑screen icon (so it looks like a real app)
- **`site.webmanifest`** — lets the game install as a full‑screen app
- **`README.md`** and **`DEPLOY.md`** — optional notes

> Tip: before you start, gather those files in the **Files** app (e.g. iCloud Drive or "On My iPhone") so you can find them when uploading.

---

## 1. Make a GitHub account

1. In Safari, go to **github.com**.
2. Tap **Sign up** and follow the prompts (email, password, a username). Your username becomes part of your game's web address, so pick something you like — e.g. `arlosdad`.
3. Verify your email when GitHub asks.

If you already have an account, just **Sign in**.

---

## 2. Create a repository (a home for the game)

A "repository" (or "repo") is just a folder that GitHub hosts for you.

1. Once signed in, tap the **+** near the top‑right of the page, then **New repository**.
   - On a phone the menus can be fiddly — if you can't find the **+**, just go straight to **github.com/new**.
2. Fill in:
   - **Repository name:** something simple with no spaces, e.g. `stone-and-sword`.
   - **Public** — leave this selected (Pages needs it to be public on a free account).
   - Tick **Add a README file** (optional, but handy).
3. Tap **Create repository**.

---

## 3. Upload the game file

1. On your new repository's page, tap **Add file** → **Upload files**.
   - If the page is showing the mobile layout and you can't see "Add file", scroll up to the file list area; the button sits just above it. You can also tap **aA** in Safari's address bar and choose **Request Desktop Website** to get the full buttons.
2. Tap **choose your files** (or the upload area) and pick **all** of these from your **Files** app: **`index.html`**, **`icon.png`**, **`site.webmanifest`** (and `README.md`, `DEPLOY.md` if you want them). You can select several at once.
3. Wait for them to finish uploading, then scroll down and tap **Commit changes** (green button).

**Important:**
- `index.html` must be named exactly that and sit at the **top level** of the repository (not inside a sub‑folder).
- `icon.png` and `site.webmanifest` must be at that **same top level**, with those exact names, or the home‑screen icon won't appear.

---

## 4. Turn on GitHub Pages

1. On the repository page, tap **Settings** (you may need **Request Desktop Website** to see the tabs clearly).
2. In the left‑hand list, tap **Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Under **Branch**, pick **`main`** and the folder **`/ (root)`**, then tap **Save**.

---

## 5. Visit your game

1. Give it about **1–2 minutes** to publish (the Pages screen will show a link once it's ready — you may need to refresh the page).
2. Your game's address will be:

   ```
   https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
   ```

   For example, if your username is `arlosdad` and the repo is `stone-and-sword`:

   ```
   https://arlosdad.github.io/stone-and-sword/
   ```

3. Open that link in Safari — the game should load straight away.

### Add it to the Home Screen (so it looks like an app)

With `icon.png` and `site.webmanifest` uploaded, you can save the game as a full‑screen app:

1. Open your game's `github.io` link in **Safari**.
2. Tap the **Share** button (the square with an arrow).
3. Tap **Add to Home Screen**, then **Add**.

You'll get the amulets icon on your home screen, and tapping it launches the game **full‑screen** with no address bar — just like a real app. (If the icon ever looks like a plain screenshot instead of the amulets, it usually means `icon.png` didn't upload to the top level, or Safari cached an old version — clear the cache and re‑add it.)

---

## Updating the game later

When you have a new `index.html`:

1. Go to your repository → tap **`index.html`** in the file list → tap the **pencil ✏️** (Edit), or use **Add file → Upload files** and upload the new one with the same name to **replace** it.
2. **Commit changes.**
3. Wait a minute for Pages to rebuild.

Phones love to show the **old** cached copy. After updating, force the new version to load:
- **iOS Safari:** Settings app → **Safari** → **Clear History and Website Data** (this clears all sites), *or* close the tab and reopen the link.
- If you saved it to your Home Screen, delete that icon and re‑add it after updating.

---

## If something goes wrong

- **The page shows a "404" / "There isn't a GitHub Pages site here."** — Pages may still be building (wait a couple of minutes), or the file isn't named `index.html` at the root. Check the file name and location.
- **You see the file's code instead of the game.** — That usually means it was opened as a "raw" link. Make sure you're visiting the `github.io` Pages address from step 5, not a `github.com/.../blob/...` link.
- **An old version keeps showing.** — It's the cache. Clear it (see "Updating" above).
- **The buttons in GitHub are hard to tap on the phone.** — Tap **aA** in Safari's address bar → **Request Desktop Website** for the full‑size layout.

That's it — happy publishing, and happy birthday to Arlo! 🎂
