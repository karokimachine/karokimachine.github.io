# KarokiMachine Games – updating content without code

Files in this repo:
- `index.html` – the website
- `admin.html` – your content manager (open at `https://YOUR-SITE/admin.html`)
- `content/weekly.json` – weekly submissions (managed by admin.html)
- `content/gallery.json` – gallery items (managed by admin.html)
- `images/` – uploaded artwork (managed by admin.html)

## One-time setup
1. Put all of the above in your GitHub repo and turn on GitHub Pages (Settings → Pages).
2. GitHub → your profile → Settings → Developer settings → Fine-grained tokens → Generate new token.
   - Repository access: **Only select repositories** → this repo
   - Permissions: **Contents → Read and write**
3. Open `admin.html` on your live site, enter your username, repo name and the token, press **Save & load content**.

## Each week
Weekly tab → choose image, type @username (and a caption if you like) → Upload.
"Clear all" wipes the week's entries when you start a new prompt. Gallery tab works the same way.
The live site refreshes about a minute after each change.

## No-token alternative
You can also edit `content/weekly.json` / `content/gallery.json` directly on github.com and drag images into the `images/` folder.
