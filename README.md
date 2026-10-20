# Español flashcards

A personal Spanish flashcard app. It runs entirely in your browser: no server and no accounts. Your words are saved on your device.

## Put it on your iPhone (GitHub Pages, about 5 minutes)

1. Sign in at https://github.com (a free account is fine) and click **New repository**. Name it `spanish`, set it to **Public** (free Pages requires a public repository), and click **Create repository**.
2. On the new repository's page, click **uploading an existing file** and drag in these five files: `index.html`, `manifest.json`, `sw.js`, `icon-180.png`, `icon-512.png`. Then click **Commit changes**.
3. Open **Settings → Pages**. Under *Build and deployment*, set **Source: Deploy from a branch**, choose **Branch: main** and **/ (root)**, and click **Save**.
4. Wait about a minute. The page shows your URL: `https://<your-username>.github.io/spanish/`.
5. On the iPhone, open that URL in **Safari**, tap **Share → Add to Home Screen**, and tap **Add**.

Always open the app from the Home Screen icon. That copy works offline, and iOS keeps its saved data. If you only use it in a Safari tab, Safari may clear the data after 7 days without a visit.

Your progress is saved separately on each device and browser. Use **Deck → Export / Import** to move it between devices or to back it up.

## Updating the app

Upload the changed file to the repository again. The Home Screen app picks up the new version on the second launch after the upload: the first launch downloads it and the next one uses it.

## How the spacing works (SM-2)

| Button | What happens |
|---|---|
| **Again** | The card comes back 3 cards later in the same session. It is also due in 10 minutes, and the word is scheduled more often from then on. |
| **Hard** | Short interval, slightly more frequent from then on |
| **Good** | Normal growth: about 1 → 3 → 8 → 20 → 50 → 115 days |
| **Easy** | Bigger jump, less frequent from then on |

Words you've missed 4 or more times get a **LEECH** tag in the Deck view. For those, add a note such as a mnemonic or an example sentence.

New words are limited to 15 per day by default. You can change this in **Deck → Settings**.
