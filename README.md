# Personal site

One static page. No build step, no Jekyll, nothing to install.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole site: layout, styles, light/dark switch |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |
| `profile.jpg` | Add this yourself. Square headshot, at least 400 x 400 px. Initials show until it exists. |
| `cv.pdf` | Your resume without your phone number. The CV links in the top bar, sidebar and bio point to it. |
| `archive/` | The four GoQuant pieces, archived with GoQuant's permission. Upload the folder as is. |

## Put it online

1. On GitHub, create a new public repository named exactly `danielvlis.github.io` (your username, then `.github.io`).
2. Unzip `site.zip`, add your `profile.jpg`, then click **Add file > Upload files** on GitHub and drag in everything, including the `archive` folder. Commit.
   - `.nojekyll` starts with a dot, so your file browser may hide it. On a Mac press Cmd+Shift+. in the upload dialog to show hidden files. If you skip it the site still works.
3. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**. Save.
4. Wait a minute or two, then open `https://danielvlis.github.io`.

## Editing later

Open `index.html` on GitHub, click the pencil icon, change the text, commit. The live site updates within a couple of minutes.

To add a new piece of work, copy one `<li class="entry">...</li>` block and change the title, link, date and description.

## Using your own domain (optional)

Buy a domain (for example `daniellis.ca`), then in **Settings > Pages > Custom domain** enter it and follow GitHub's DNS instructions. Tick **Enforce HTTPS** once it becomes available. Update the `og:url` line near the top of `index.html` to match.
