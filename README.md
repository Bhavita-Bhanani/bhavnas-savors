# Bhavna's Savors

A single-page website for **Bhavna's Savors**, a homemade snacks and mithai brand based in Karachi. Built as a static site — no build step, no framework, no dependencies beyond Google Fonts.

## Features

- Animated hero section with floating photo cards and a looping marquee ticker
- Sticky, responsive navigation with a mobile slide-in menu
- Story / About section
- Why Choose Us section
- Tabbed menu with categories, pricing by piece / dozen / weight, and dish photography
- Photo gallery
- Customer reviews
- Contact section with a WhatsApp-integrated enquiry form (includes phone format validation)
- Floating WhatsApp button
- Fully responsive (mobile, tablet, desktop)

## Tech

- Plain HTML5, CSS3 (custom properties, grid, flexbox, keyframe animations), vanilla JavaScript
- Fonts: Fraunces, Outfit, Space Mono (via Google Fonts)
- Photography sourced from [Pexels](https://www.pexels.com) (free license, no attribution required)

## Project structure

```
bhavnas-savors.html   # the entire site (markup, styles, and scripts in one file)
README.md
```

## Running locally

No build tools needed — just open the file:

```
# Windows
start bhavnas-savors.html

# macOS
open bhavnas-savors.html

# Linux
xdg-open bhavnas-savors.html
```

Or serve it locally for a more realistic preview:

```
python -m http.server 8000
# then visit http://localhost:8000/bhavnas-savors.html
```

## Deploying with GitHub Pages

1. Push this repo to GitHub (see commands below).
2. On GitHub: **Settings → Pages → Source → Deploy from a branch → main / (root)**.
3. Your site will be live at `https://<your-username>.github.io/<repo-name>/bhavnas-savors.html`.

(Optional: rename `bhavnas-savors.html` to `index.html` if you want it served at the root URL instead.)

## License

Site code is free to use and modify for this project. Photography is from Pexels under their free-to-use license.
