# Fintara — Startup Profile Website

A single-page company profile for a financial services startup. Pure HTML/CSS/JS — no build step, works directly on GitHub Pages.

## Publish on GitHub Pages

1. Create a new repository on GitHub (e.g. `company-profile`).
2. Upload `index.html` and `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
5. After a minute or two your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

## Customize

| What | Where in `index.html` |
|---|---|
| Company name | Search for `Fintara` and replace |
| Brand colors | `:root` block at the top of `<style>` (`--brand`, `--accent`) |
| Services | `<section id="services">` — each `.card` is one service |
| Numbers / stats | `<div class="stats">` — replace with real figures |
| Team | `<section id="team">` — names, roles, bios |
| Contact details | `<section id="contact">` |
| Legal disclaimer | Footer, `.footer-bottom` |

## Contact form

GitHub Pages can't process form submissions on its own. To make the form work:

1. Create a free form at [formspree.io](https://formspree.io).
2. Copy your form ID and replace `YOUR_FORM_ID` in `index.html`.

## Custom domain (optional)

In **Settings → Pages → Custom domain**, enter your domain and follow GitHub's DNS instructions.
