# Odvodi — tangenta v točki

Self-serve learning material for **odvodi** (derivatives): one matura task —
the tangent line at a point — decomposed into the minimal set of concepts,
each with its own memory encoding and visualization.

- **Latest:** https://maad-mood.github.io/odvodi/
- **Versions index:** https://maad-mood.github.io/odvodi/versions.html

## Versioning
- Root `/` always serves the **latest** snapshot (`index.html`).
- Each release is also frozen at a permanent URL `/rN/` (e.g. `/r1/`) and never changes.
- Each release is tagged in the source project as `site-rN` (pointing at the commit that built it).

## Publishing a new release (rN)
From the source project, rebuild `prototypes/odvodi-app/bundle.html`, then in this repo:
```
cp <source>/prototypes/odvodi-app/bundle.html index.html   # update latest
mkdir rN && cp index.html rN/index.html                    # freeze this release
# add a row to versions.html
git add -A && git commit -m "Release rN (<source-commit>)" && git push
# in the source repo: git tag -a site-rN <commit> -m "Published as rN"
```
