# Musab & Co. Portfolio

Single-page dashboard. No build step. Just `index.html`.

## Put it live on GitHub Pages

1. Go to github.com, click **New repository**. Name it `musab-portfolio`. Choose **Public**. Click **Create repository**.
2. On the repo page click **uploading an existing file**. Drag in `index.html` and `README.md`. Click **Commit changes**.
3. Open **Settings > Pages**.
4. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, Folder to **/ (root)**. Click **Save**.
5. Wait 1 to 2 minutes. Your site is at `https://YOUR-USERNAME.github.io/musab-portfolio/`.

To update later: open `index.html` in the repo, click the pencil icon, edit, commit.

## Google Sheets sync

Both sheets must be shared as **Anyone with the link can view**.
Sheet IDs and the `AUTO` switch are at the top of the script in `index.html`.

- `AUTO=true`: the page pulls both sheets every time it opens.
- `AUTO=false`: only the Sync buttons pull data.

## Before you make it public

The page contains your real numbers and the sheet IDs. Anyone with the link can read them.
Options: use dummy numbers in the `DEF` block before publishing, or keep the repo private
(GitHub Pages on private repos needs a paid plan).
