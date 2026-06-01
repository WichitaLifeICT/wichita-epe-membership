# Wichita EPE Membership

A static landing-page prototype for **Wichita EPE Membership — Every Person Empowered**: a free,
community-powered membership that helps Wichita residents take the next step toward stability,
progress, and contribution.

## Live site

This site is published with **GitHub Pages** from this repository. Once Pages is enabled
(see below), it is available at:

```
https://wichitalifeict.github.io/wichita-epe-membership/
```

## What's here

| File         | Purpose                                                                 |
| ------------ | ----------------------------------------------------------------------- |
| `index.html` | The entire site — HTML, CSS, and JavaScript in one self-contained file. |
| `.nojekyll`  | Tells GitHub Pages to serve the files as-is (skips Jekyll processing).  |
| `README.md`  | This file.                                                              |

There is no build step. The page uses only inline CSS/JS plus
[Google Fonts](https://fonts.google.com/) (Fraunces + Outfit) loaded over a CDN.

## Viewing locally

Open `index.html` directly in a browser, or serve the folder:

```bash
# Python 3
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Enabling GitHub Pages

GitHub Pages is configured per-repository in **Settings → Pages** (this can't be set from
the codebase):

1. Go to **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Select the branch (e.g. `main`) and the `/ (root)` folder, then **Save**.
4. Wait for the deployment to finish; the public URL appears at the top of the Pages settings.

## Customizing

- **Theme:** edit the CSS custom properties in the `:root{ … }` block near the top of
  `index.html` to re-theme the whole page (navy, gold, cream, sage, coral).
- **Content:** the section data (steps, membership levels, partners, benefits, stories,
  Thrive Lights domains) lives in the `/* ---------- data ---------- */` block in the
  `<script>` at the bottom of `index.html`.

## Status

Prototype / for demonstration only. The membership form and call-to-action buttons are
placeholders and are not yet connected to a backend.
