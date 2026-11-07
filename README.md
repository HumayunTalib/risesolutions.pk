# RISE Energy – Solar Solutions

Static website for https://risesolutions.pk (plain HTML/CSS/JS, no build step).

## Files
- `index.html` – the whole site
- `assets/` – logo, favicon, photos (replace photos with your own, same filenames)
- `CNAME` – custom domain for GitHub Pages
- `robots.txt`, `sitemap.xml` – SEO

## Deploy on GitHub Pages
1. Create a repo and upload all files to the root (keep the `assets` folder).
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)` → Save.
3. Settings → Pages → Custom domain: `risesolutions.pk`, then enable *Enforce HTTPS*.
4. At your domain registrar, add A records for `@` pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`, and a CNAME for `www` pointing to `<your-username>.github.io`.

Delete the `CNAME` file if you only want the default `<username>.github.io/<repo>` URL.

## Edit
- WhatsApp number/message: `N` and `M` variables at the bottom of `index.html`.
- Google Maps: replace the `#map` block in the Contact section with your embed iframe.
