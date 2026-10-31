# Pease Productions website

A one-page static site (plain HTML, no build step). Vercel serves it as-is.

## Adding a film description

Open `index.html` and search for `DESCRIPTION:`. Each film has one, just under its year. Paste the description on the next line, one `<p>` per paragraph:

```html
<div class="about">
  <p>First paragraph of the description.</p>
  <p>Second paragraph.</p>
</div>
```

## Changing the contact email

Search `index.html` for `EMAIL:` and change the address in both spots on the line below it (the `mailto:` link and the visible text).

## Adding a new film

Copy one whole `<article class="film">…</article>` block, paste it where it should appear, and change the poster image, title, year and festival list. Put two poster sizes in `images/`: a full-size one and a `-720` one about 720px wide.

## Files

- `index.html` – the whole site
- `images/` – logo, posters, and the link-preview image (`share.jpg`)
- `favicon.png`, `apple-touch-icon.png` – browser and phone icons
