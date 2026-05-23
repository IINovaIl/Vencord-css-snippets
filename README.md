# Vencord CSS Snippets

A collection of CSS snippets for [Vencord](https://vencord.dev/), hosted via GitHub Pages so your Quick CSS editor stays clean.

## Usage

Paste one or more `@import` lines into your Vencord **Quick CSS** editor instead of the raw CSS.

### Import a single snippet

```css
@import url(https://YOUR_USERNAME.github.io/vencord-css-snippets/snippets/NitroCardBanner/NitroCardBanner.css);
```

### Import everything at once

```css
@import url(https://YOUR_USERNAME.github.io/vencord-css-snippets/index.css);
```

---

## Snippets

| Snippet | Description | Import |
|---|---|---|
| **NitroCardBanner** | Extends the banner image behind the Nitro card with a blurred, gradient-masked overlay effect. | `@import url(https://YOUR_USERNAME.github.io/vencord-css-snippets/snippets/NitroCardBanner/NitroCardBanner.css);` |

---

## Adding a new snippet

1. Create a folder under `snippets/` named after your snippet (PascalCase recommended).
2. Add a `.css` file inside it with the same name.
3. Add an `@import` line for it in `index.css`.
4. Add a row to the table above.

## GitHub Pages setup

1. Go to **Settings → Pages** in this repository.
2. Set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. Save — your snippets will be live at `https://YOUR_USERNAME.github.io/vencord-css-snippets/` within a minute.

> **Remember to replace `YOUR_USERNAME`** in all import URLs with your actual GitHub username.
