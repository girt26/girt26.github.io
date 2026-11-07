# main

Landing page for girt26.github.io. A quiet editorial index of the things I host.

## Editing the index

Open `index.html` and edit the `<ol class="link-list">` directly. Each row is one `<li>`:

```html
<li class="link-item">
  <a class="link-row" href="https://girt26.github.io/zeuscraft">
    <span class="row-number" aria-hidden="true">02</span>
    <span class="row-body">
      <span class="row-title-wrap">
        <!-- icon svg (optional) -->
        <span class="row-title">Eaglercraft 26.2</span>
        <span class="row-tag">Game</span>
      </span>
      <span class="row-note">Minecraft 26.2</span>
    </span>
    <span class="row-url" aria-hidden="true">girt26.github.io/zeuscraft</span>
    <span class="row-arrow" aria-hidden="true">↗</span>
  </a>
</li>
```

- Keep `.row-url` in sync with the link target. It is hidden from screen readers because the link already exposes the URL.
- Row numbers are decorative. The entry count updates automatically from the number of `<li>` elements.
- The page works without JavaScript. JS only fills in the year, the entry count, and the theme toggle.

## Theme

The site follows the visitor's system light/dark preference by default. The toggle in the masthead saves an override in `localStorage`; remove the `theme` key to return to system behaviour.

## Files

- `index.html` — the landing page
- `404.html` — GitHub Pages not-found page
- `sitemap.xml` — sitemap for search engines
- `apple-touch-icon.png` — iOS home-screen icon
