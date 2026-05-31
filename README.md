# i love you heart page

A tiny static HTML page with an animated heart made from `i love you` text.

## Files

- `index.html` — the full website in one file.
- `.nojekyll` — tells GitHub Pages to publish the site as plain static files.
- `CNAME.example` — example for a custom domain. Rename it to `CNAME` and put your real domain inside when you are ready.

## Local preview

```bash
uv run python -m http.server 8000
```

Open:

```text
http://localhost:8000
```

## GitHub Pages

1. Create a new public repository on GitHub.
2. Upload these files to the repository root.
3. Open `Settings` → `Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Select branch `main` and folder `/ (root)`.
6. Save and open the Pages link after deployment finishes.

## Custom domain

In `Settings` → `Pages` → `Custom domain`, add your domain, then configure DNS records at your domain provider.

For `example.com`, create GitHub Pages `A` records. For `www.example.com`, create a `CNAME` record pointing to your GitHub Pages address, for example `username.github.io`.
