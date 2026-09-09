# Clélia Seyfried — Personal Site

A single-page personal landing site (static HTML/CSS/JS, no build step).

## Structure
- `index.html` — the whole site (inline CSS + JS)
- `images/` — cover banner and headshot

## Contact form
The contact form posts to [Formspree](https://formspree.io). Replace
`YOUR_FORM_ID` in `index.html` with the ID from your Formspree form
(pointed at clelia.seyfried@gmail.com) to receive submissions by email.

## Local preview
Open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment
Hosted on GitHub Pages. Pushing to the default branch publishes the site.
