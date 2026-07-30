# Shivamraj Domestic Help Agency — Website

Plain HTML/CSS/JS. No npm, no build step, no framework — open
`index.html` in a browser and it works, anywhere, forever.

## Files

```
shivamraj-site/
├── index.html   ← all page content & structure
├── styles.css   ← all colors, spacing, layout, responsive rules
├── script.js    ← navbar scroll behavior, hamburger menu, animations
```

## How to preview it

Just double-click `index.html` — it opens directly in your browser.
No installation, no terminal, no server needed.

## How to deploy it (Netlify)

1. Go to [app.netlify.com](https://app.netlify.com)
2. Drag the whole `shivamraj-site` **folder** onto the dashboard
3. Live in under a minute, with a free URL

To update the live site later: make your edits, then drag the
folder onto Netlify again (or connect it to GitHub for automatic
updates on every push — ask if you want that set up).

## Common edits — where to find them

| What you want to change | Which file | What to look for |
|---|---|---|
| Phone number / WhatsApp number | `index.html` | Search for `919016723136` (appears ~8 times) |
| Business name, tagline | `index.html` | Near the top, inside `<nav class="navbar">` |
| Service names/descriptions | `index.html` | Inside `<section ... id="services">`, one `.service-card` div per service |
| Prices (if you add pricing later) | `index.html` | Would go in a new section — ask and I'll add one |
| Testimonials | `index.html` | Inside `<section ... id="testimonials">` |
| Address, email | `index.html` | Inside `<section ... id="contact">` |
| Colors (brand teal / gold) | `styles.css` | Top of file, inside `:root { ... }` — change `--teal` and `--gold` and the whole site updates |
| Fonts | `styles.css` | `--font-head` and `--font-body` variables, plus the Google Fonts `<link>` in `index.html` `<head>` |
| Spacing between sections | `styles.css` | `.section { padding: ... }` |

## Why no images are used

Every icon on this site (🧹 🍳 👶 etc.) is a plain emoji character
in the HTML — not an image file. This was a deliberate choice: it
means nothing can ever go missing or break due to a wrong filename,
case-sensitivity issues (Windows vs. Linux servers), or a forgotten
upload. If you'd like real photographs instead of icons later, send
me the image files and I'll swap them in — just ask.

## If you want to add a new section later

Copy an existing `<section>` block in `index.html` as a starting
template, give it a new `id`, and add a matching nav link in the
navbar. Send me the request any time and I can do this for you
directly instead.
