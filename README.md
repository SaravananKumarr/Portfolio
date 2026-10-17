# Saravanan Kumar — Portfolio

Personal portfolio of **Saravanan Kumar**, full-stack developer and B.Tech CSE (Cyber Security) student at SRM Institute of Science and Technology, Tiruchirappalli.

## Features
- Sunset sky with a three-layer parallax city skyline
- Original hooded "cyber guardian" character that swings in on page load
- Hanging security drone and circuit-trace hover effects
- Home, About, Projects and Experience pages (hash routing, no build step)
- Phone-style music player with five original tracks synthesised live using the Web Audio API (no audio files)
- Responsive layout with a mobile tab bar; respects reduced-motion settings

## Project structure
```
.
├── index.html                    # The whole site: HTML, CSS and JavaScript
├── 404.html                      # Sends unknown URLs to the site's "Route not found" screen
├── favicon.svg                   # Browser tab icon
├── .nojekyll                     # Tells GitHub Pages to serve files as-is
├── .gitignore
├── LICENSE                       # MIT
└── .github/workflows/deploy.yml  # Auto-deploys to GitHub Pages on every push to main
```

## Run locally
Open `index.html` in any browser. Nothing to install.

## Deploy on GitHub Pages
1. Push or upload these files to the `main` branch of a GitHub repository.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **GitHub Actions**.
4. Open the **Actions** tab and wait for "Deploy portfolio to GitHub Pages" to finish (about a minute).
5. The site is live at `https://<your-username>.github.io/<repo-name>/`.

Every later push to `main` redeploys automatically.

> Tip: name the repository `<your-username>.github.io` to publish at `https://<your-username>.github.io/` with no repo name in the URL.

## Contact
- Email: kumarsaravanan2005@gmail.com
- LinkedIn: https://www.linkedin.com/in/saravanank-94753b2b4
