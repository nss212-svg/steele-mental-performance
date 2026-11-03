# Steele Mental Performance

Program website for Steele Mental Performance, mental performance coaching for athletes in every sport. Built on the **tempo.** platform.

## Hosting: Cloudflare Pages (free)

1. Go to https://dash.cloudflare.com → **Workers & Pages** → **Create** → **Pages** tab → **Connect to Git**.
2. Pick this repo.
3. Build settings: **Framework preset:** None. **Build command:** leave empty. **Build output directory:** `public`.
4. Click **Save and Deploy**. The site goes live at an address like `steele-mental-performance.pages.dev`.

Every push to `main` redeploys automatically.

**Custom domain (optional):** the project → **Custom domains** → add the domain (for example `steelementalperformance.com`). If the domain is bought through Cloudflare, DNS is set up automatically.

## Files

```
public/index.html    the whole site (styles and script inline)
public/favicon.svg   browser tab icon
```

Colors are at the top of the `<style>` block in `index.html` (navy, steel blue, gold from the program flyer).
