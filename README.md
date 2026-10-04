# Athetis

A personal-brand website inspired by amber metro departure boards. Black, orange, beige, and the supplied MUSICNET font.

## Run locally

No installation or build required. From this repository:

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000.

## Pages

- `dist/index.html`: home and animated departure board
- `dist/work/index.html`: filterable portfolio with expandable project details
- `dist/about/index.html`: personal introduction
- `dist/contact/index.html`: social links

All copy, project entries, links, and page templates are in `dist/assets/app.js`. Colors and layout are in `dist/assets/style.css`.

The Visual studies and Words in transit entries are introductory archive placeholders. Replace them with finished work as it becomes available. Verify personal copy and social links before public release.

## Hosting

Serve `dist` as the website root. Relative asset paths support GitHub Pages project repositories. If using GitHub Pages, deploy the `dist` folder with the supplied workflow and select GitHub Actions as the Pages source.

## Assets

MUSICNET.ttf was supplied by the owner; verify its license before distributing or using commercially. `platform.webp` is an AI-generated atmospheric metro image. No third-party scripts or tracking.

## Accessibility

Keyboard navigation, accessible project disclosures and filters, reduced-motion support, and a manual pause control are included.
