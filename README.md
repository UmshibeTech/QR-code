# Mshibe Wedding Film QR page

## Run locally

Open a terminal in this folder and run:

```sh
python3 serve.py
```

Then open <http://localhost:8000/qrcode.html>. To use a different port:

```sh
python3 serve.py --port 5501
```

Keep the server running while previewing the page locally. The QR code always
points to the public page at
<https://umshibetech.github.io/QR-code/qrcode.html>, including when viewing a
local preview, so scanning it opens the published page rather than `localhost`.

The QR-code library is loaded from a CDN, so an internet connection is needed
for QR generation. For a public, shareable QR code, publish the page to a web
host and use its HTTPS address. This repository deploys the page to GitHub Pages
when changes are pushed to `main`. The “Copy Website Link” button copies the
official website at <https://umshibetech.github.io/website/>.
