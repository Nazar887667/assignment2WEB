# Assignment 2 — Advanced CSS (Flexbox & Grid)

A small multi-page site built to practice Flexbox and CSS Grid without
frameworks or floats.

## Pages

| File | Task | What it demonstrates |
|---|---|---|
| `index.html` | Task 0 (navbar) | Shared flex navbar, links to every task page |
| `cards.html` | Task 1 | Flexbox row of equal-height cards with hover lift |
| `grid-layout.html` | Task 2 | `grid-template-areas` for header/sidebar/main/footer |
| `gallery.html` | Task 3 | 3-column image grid with a hover caption overlay |
| `portfolio.html` | Task 4 | Grid for page layout, Flexbox inside each card |

## Structure

```
index.html
cards.html        cards.css
grid-layout.html  grid-layout.css
gallery.html      gallery.css
portfolio.html    portfolio.css
style.css          (shared reset, variables, navbar)
```

Each task page loads `style.css` first for shared styles, then its own
stylesheet for that page's layout.

## Running locally

No build step — open `index.html` directly in a browser, or serve the
folder with any static server, e.g.:

```
npx serve .
```

## Deploying

**GitHub Pages:** push this folder to a repo, then in
*Settings → Pages* set the source to the `main` branch, root folder.

**Netlify:** drag the folder onto app.netlify.com/drop, or connect the
GitHub repo for automatic deploys.
