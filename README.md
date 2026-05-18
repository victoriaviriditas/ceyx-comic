
An interactive three-section flip-book of the parallel narrative comic 'Ceyx' by Kristen Haas Curtis. 

## Structure

- `index.html` — self-contained app, no build step needed
- `images/` — all page artwork (44 files)
  - `p01-full.jpg` … `p17-full.jpg` — full pages (1, 2, 15, 16, 17)
  - `p03-top.jpg`, `p03-mid.jpg`, `p03-bot.jpg` … — three strips per split page (3–14)

## Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "ceyx interactive zine"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/ceyx-zine.git
git push -u origin main
```

Then: Settings → Pages → Source: main / root → Save.

Live at: `https://YOUR-USERNAME.github.io/ceyx-zine/`

## Embed in WordPress

```html
<iframe src="https://YOUR-USERNAME.github.io/ceyx-zine/"
  width="100%" height="700" style="border:none"></iframe>
```

Paste into a WordPress Custom HTML block. Use a Full Width page template.
