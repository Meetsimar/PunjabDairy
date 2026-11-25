# Punjab Dairy – Ultimate

Website for Punjab Dairy – Ultimate (Ludhiana, Punjab). Plain HTML and CSS, no build step.

## Files

- `index.html` – the whole site
- `style.css` – all styling
- `images/` – put product photos here (create the folder when you add the first photo)

## Adding a product photo

In `index.html`, replace a `<div class="photo">Photo: …</div>` with:

```html
<img class="photo" src="images/ghee.jpg" alt="Punjab Dairy pure ghee" loading="lazy">
```

Use JPG or WebP files about 1200px wide and under 300 KB each.

## Publishing with GitHub Pages

Repository **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save.**
The site appears at `https://<username>.github.io/<repository>/` after a minute or two.
