# CUSP — Premium Mobile Review + Rewards Pages

Two premium, mobile-first, single-page screens (no backend) designed to feel like a native iPhone experience.

## Pages

- **Review screen**: `index.html`
- **Referral + rewards screen**: `referral.html`

> Note: The `*.html.md` files are earlier working versions and may not render in browsers (escaped HTML). Use the `.html` files for preview + deployment.

## Quick preview (local)

1. Open File Explorer
2. Go to this folder:
   - `C:\Users\ewf83\OneDrive\Desktop\index.html`
3. Double-click:
   - `index.html`

## Deploy with GitHub Pages

1. On GitHub, open your repo and go to **Settings → Pages**
2. Under **Build and deployment**:
   - **Source**: Deploy from a branch
   - **Branch**: `main` / `(root)`
3. Save and wait a minute

Your site should appear at:
- `https://edgarferguson-dev.github.io/cusp/`

## Customize

### Set your real Google review link

In `index.html`, find:

```html
href="YOUR_GOOGLE_REVIEW_LINK_HERE"
```

Replace it with your actual Google Review URL.

### Update your referral link/domain

In `referral.html`, update the value in the referral input:

```html
value="https://cusp.example/ref/CUSP-7K2A"
```

## Tech

- Plain **HTML + CSS + a tiny bit of JS** (touch interactions + share/copy)
- **Mobile-first**, glassmorphism UI, subtle motion, safe-area aware

