# Parinita Kumari — Portfolio

Personal portfolio site. Single-page, no build step, no dependencies —
one self-contained `index.html`.

**Live:** _add your URL here_

## Stack

Plain HTML + CSS + a little vanilla JS. Everything is inlined:

- Brand logos are an inline SVG sprite (Simple Icons paths), so there are
  no runtime requests for icons
- Company logos are base64 data URIs
- Theme is driven by CSS custom properties (`--accent`, `--tint-*`), so the
  whole palette can be retuned from one block
- Scroll reveal and the progress bar are added by JS, so the page still
  renders fully with JS disabled

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire site |
| `profile_pic.png` | Headshot used in the hero |
| `Parinita_Kumari_Resume.pdf` | Linked from the nav and the CTA |

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploying with GitHub Pages

Settings → Pages → Source: `main` / root. The site is static, so it works
as-is with no build step.
