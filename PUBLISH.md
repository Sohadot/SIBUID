# Publish SIBUID Reference v0.1

Target repository: `Sohadot/SIBUID`

The package is designed to live at the repository root.

## Git publish

```bash
git clone https://github.com/Sohadot/SIBUID.git
cd SIBUID
# Copy the contents of SIBUID_reference_v0.1 into this directory.
git add .
git commit -m "release: publish SIBUID reference surface v0.1"
git push origin main
```

## GitHub Pages

Use the repository root as the Pages publishing source. The package already contains:

- `index.html`
- route directories with `index.html`
- `.nojekyll`
- `CNAME` set to `sibuid.com`
- `robots.txt`
- `sitemap.xml`

DNS must point `sibuid.com` to the selected GitHub Pages configuration before the custom domain resolves.

## Post-publish checks

1. Confirm all five routes return HTTP 200.
2. Confirm the canonical URLs resolve to `https://sibuid.com/...`.
3. Confirm `https://sibuid.com/sitemap.xml` and `/robots.txt` are reachable.
4. Add the domain property to Google Search Console and submit `sitemap.xml`.
5. Do not expand the conceptual surface before a new dated decision record.
