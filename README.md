ASR Dinks — Amritsar Dinks Padel Rankings

Live site: asrdinks.in

A single-page site showing ADP (Amritsar Dinks Padel) player rankings, built with plain HTML/CSS.

Tech
Static HTML/CSS, no build step or dependencies
Fonts: Archivo, Space Mono, Work Sans via Google Fonts
Hosted on GitHub Pages with a custom domain
Running locally

Just open index.html in a browser, or serve it with any static server, e.g.:

bash
npx serve .

or the VS Code "Live Server" extension.

Deployment

Pushing to the main branch automatically updates the live site via GitHub Pages. Custom domain is configured in the repo's CNAME file and in the registrar's DNS settings (A records pointing to GitHub Pages IPs).

Updating rankings

Player rankings currently live directly in index.html. To update them, edit the relevant section and push to main — changes go live within a minute or two (may take longer if GitHub's CDN cache hasn't cleared).

License

© 2026 ASR Dinks. All rights reserved.
