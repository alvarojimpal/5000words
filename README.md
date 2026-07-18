# 5000words.app

Marketing site for [#5000words](https://apps.apple.com/app/id1234793120), the iOS app for learning the 5,000 most common words of a language by speaking them.

Plain static HTML/CSS/JS (no build step, no Jekyll — note `.nojekyll`), deployed via GitHub Pages with the custom domain in `CNAME`.

- `index.html` — landing page (hero demo loop, features, privacy, languages)
- `styles.css` — shared design system (Fraunces / Figtree / Fragment Mono, dark + iOS-blue to match the app)
- `privacypolicy/` and `contact-me/` — kept at these paths because the App Store listing links them
- `404.html` — GitHub Pages picks this up automatically

Preview locally: `python3 -m http.server 8000` and open http://localhost:8000.
