# Evergreen Applications

Marketing site for Evergreen Applications, listing the apps we build (currently [SpaceHub](apps/spacehub/)).

## Structure

```
index.html          Main landing page
css/style.css        Site-wide styles (brand colors: green #163923, light grey background)
js/main.js            Small page scripts
images/                Logo and app icons (add your own here)
apps/spacehub/          SpaceHub app page (placeholder, themed separately)
```

## Adding the logo

Drop the following files into `images/`:

- `logo.png` — company logo shown in the header
- `favicon.png` — browser tab icon
- `spacehub-icon.png` — icon shown on the SpaceHub card

## Local preview

Open `index.html` directly in a browser, or serve the folder locally, e.g.:

```
python3 -m http.server
```
