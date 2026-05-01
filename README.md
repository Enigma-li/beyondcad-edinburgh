# Beyond CAD Workshop Website

A lightweight static website package for GitHub Pages.

## Included files

- `index.html` — homepage
- `styles.css` — styling
- `assets/logo.png` — workshop logo and favicon
- `assets/footer-edinburgh.webp` — footer skyline image
- `assets/poster.png` — poster image
- `assets/qr-beyondcad.png` — QR code for website link
- `assets/icons/*.svg` — UI icons used across sections
- `assets/people-circle/*.png` — speaker and organizer portraits used by the site
- `assets/sponsors/` — host/sponsor logos for footer

## How to publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload all files in this folder to the repository root.
3. In GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder.
6. Save. GitHub will publish the site in a minute or two.

## Quick customization

- Update dates in `index.html`
- Replace the email and website links in the contact section
- Update agenda items and speaker/organizer affiliations in `index.html`
- Add or replace logos in `assets/sponsors/` and update footer labels
- Replace speaker portraits in `assets/people-circle/` (keep filenames consistent)

## Notes

- Speaker and organizer cards are already using portrait images (`.webp`).
- The bottom information strip and sponsor bar are responsive for desktop/mobile.
