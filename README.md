# PassGen — Simple Password Generator

A single-page, client-side password generator. Everything runs in the browser
using the Web Crypto API (`crypto.getRandomValues`), so no password ever leaves
your device.

## Features

- Adjustable length (4–64 characters)
- Toggle uppercase, lowercase, numbers, and symbols
- Live password strength meter
- One-click copy to clipboard
- Zero dependencies, zero build step — just open `index.html`

## Run locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000> in your browser.
