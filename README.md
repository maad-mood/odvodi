# Odvodi — tangenta v točki

Self-serve learning material for **odvodi** (derivatives): one matura task —
the tangent line at a point — decomposed into the minimal set of concepts,
each with its own memory encoding and visualization.

**Live:** https://maad-mood.github.io/odvodi/

`index.html` is a single self-contained file (all JS/CSS/fonts/visuals inlined).
It's a point-in-time snapshot exported from the source project's
`prototypes/odvodi-app/bundle.html`.

## Updating
Rebuild the bundle in the source project, then:
```
cp <source>/prototypes/odvodi-app/bundle.html index.html
git commit -am "Update snapshot" && git push
```
