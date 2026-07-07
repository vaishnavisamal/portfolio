# Vaishnavi Samal — Portfolio

Your personal portfolio website, ready to publish on GitHub Pages.

## Files
- **`index.html`** — the page structure and content
- **`style.css`** — all styling (navy & gold theme, layout, responsive rules)
- **`README.md`** — this file

## How to publish on GitHub Pages

1. Go to your repository: `github.com/vaishnavisamal/samalengineers`
2. Click **Add file → Upload files**
3. Drag in **both** `index.html` and `style.css` from this folder (this replaces your current site files — make sure both are uploaded together, since the page won't style correctly without `style.css` sitting alongside it)
4. Commit the change (top right, "Commit changes")
5. Your site will update automatically at:
   `https://vaishnavisamal.github.io/samalengineers/`
   (usually live within 1–2 minutes)

If you'd rather use git from your computer instead of the web upload:
```bash
git clone https://github.com/vaishnavisamal/samalengineers.git
cd samalengineers
# copy the new index.html and style.css into this folder, replacing the old ones
git add index.html style.css
git commit -m "Update portfolio: navy/gold design, updated skills"
git push
```

## Editing later
- Update text, roles, or links → edit `index.html`
- Update colors, fonts, spacing, or layout → edit `style.css`
- Main color variables are defined at the top of `style.css` under `:root` (e.g. `--navy`, `--gold`) — changing these updates the color scheme throughout the whole site
