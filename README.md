# Sillycon

Developer website for **Sillycon**, an independent mobile game studio (Google Play developer account).

Live: https://zakriyaamir.github.io/sillycon/

| Page | URL |
|---|---|
| Home | https://zakriyaamir.github.io/sillycon/ |
| Privacy Policy | https://zakriyaamir.github.io/sillycon/privacy-policy.html |
| Data Deletion | https://zakriyaamir.github.io/sillycon/data-deletion.html |
| Terms of Service | https://zakriyaamir.github.io/sillycon/terms.html |
| Support | https://zakriyaamir.github.io/sillycon/support.html |

Plain static HTML/CSS served by GitHub Pages from `main` / root. No build step.

## Adding a game
In `index.html`, copy one `<article class="game">` block inside the Games section, change the image, tags, title and text, and add the Google Play link when it's live.

## Editing shared header/footer
The header and footer are repeated in each HTML file. Update all pages when changing navigation.

## app-ads.txt
Not included. AdMob looks for `app-ads.txt` at the root of the developer website domain (e.g. `https://example.com/app-ads.txt`), so it can't be served from this `/sillycon/` subpath. Use a custom domain for this repo or host it at the root of a domain you control.

Contact: sillycon1998@gmail.com
