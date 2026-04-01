# Nahal Ventures Website

Premium dark-themed static website for **Nahal Ventures** (private investment vehicle / family office), including:

- Main landing page (`main.html`)
- Separate investor login page (`investor-login.html`)
- Shared styling and motion system (`style.css`)
- Lightweight UI behavior (`main.js`)

## Run locally

Because this is a static site, you can run it with any web server.

### Option 1: Python

```bash
python3 -m http.server 8000
```

Then open:

- `http://localhost:8000/main.html`
- `http://localhost:8000/investor-login.html`

### Option 2: VS Code Live Server

Open the repo and launch Live Server from `main.html`.

## Customization notes

- Replace logos in `Img/logo.png` (and related assets if needed).
- Update copy directly in `main.html` and `investor-login.html`.
- Contact email placeholder is in the contact section of `main.html`.
- Login form is frontend-only and intentionally scaffolded for backend auth integration.
