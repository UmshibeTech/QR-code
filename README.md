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
<https://www.mshibeweddingfilms.co.za/qrcode.html>, including when viewing a
local preview, so scanning it opens the published page rather than `localhost`.

The QR-code library is loaded from a CDN, so an internet connection is needed
for QR generation. The live page is served by the existing `UmshibeTech/media`
GitHub Pages site at
<https://www.mshibeweddingfilms.co.za/qrcode.html>. To publish changes to this
page, synchronize `qrcode.html` and `IMG_0214.JPG` to that site's repository.
The website root remains the main website. The “Visit Our Website” link opens
<https://www.mshibeweddingfilms.co.za/>.
