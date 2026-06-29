# CloudMoon static bundle

This repository contains a cleaned-up static CloudMoon bundle. The root now keeps only the four current HTML entry points:

- `index.html` — all-in-one launcher / primary entry point
- `portal.html` — portal-only entry point
- `main.html` — combined portal and play experience
- `play.html` — play-only entry point

The original dated exports were preserved under `archive/dated-builds/` for comparison or rollback. Duplicate SVG exports were moved there as well, while the latest SVG variants are available with stable names in `assets/svg/`.

## Directory layout

```text
.
├── index.html
├── main.html
├── play.html
├── portal.html
├── assets/svg/              # current SVG assets with stable names
├── archive/dated-builds/    # original dated HTML/SVG exports
└── run-site/images/         # image assets referenced by play.html
```

## Notes

- The current root HTML files were taken from the `260605` dated export set.
- Historical files are archived rather than deleted so behavior can be compared if needed.
- `play.html` references image assets from `run-site/images/`.
