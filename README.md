# Computational Geometry Consultancy

Static website for independent scientific and computational geometry consultancy by Salah-Eddin Gherbi.

**Status:** deployment-ready draft, awaiting review. No live site or GitHub repository has been created by this package.

## Start locally

```bash
python3 -m http.server 8000
# http://localhost:8000
```

The site itself needs no build system, runtime dependencies, tracking or external JavaScript. All illustration assets are included locally. The only outbound links are to the author's public research material and the contact email link.

## Publish on GitHub Pages

1. Create a **new public, empty** GitHub repository named `computational-geometry-consultancy` on the `salahealer9` account. (Do not initialise with an automatic README if using command-line pushing.)
2. Clone that repository locally, copy all files from this package into its root, preserving `assets/` and `.nojekyll`, and commit/push to `main`.
3. In the repository, open **Settings → Pages → Build and deployment**. Set **Source: Deploy from a branch**, **Branch: main**, **Folder: /(root)**, then save.
4. The anticipated URL is `https://salahealer9.github.io/computational-geometry-consultancy/` **only once GitHub Pages successfully publishes it**.
5. Check the deployed images and mailto link from both mobile and desktop before using it in outreach.

Alternatively, once the empty repository exists and is available to the connected GitHub app, its files can be uploaded directly through the connector.

## Scope and permissions

The site is a commercial introduction, **not a structural engineering service or prior-client project gallery**. Some examples are published research artifacts or new static projections of previously certified research data.

No private repository source code or unreleased datasets are included here. For figure provenance and exact distinctions between figures and certified roots, see [SOURCES.md](SOURCES.md).

Contact: [salahealer@gmail.com](mailto:salahealer@gmail.com)

## Live interactive research examples

The website now links to the author's independently hosted GitHub Pages viewers:

- Plane Sri Yantra certified atlas: https://salahealer9.github.io/sri-yantra-constraint-viewer/
- Spherical Sri Yantra certified atlas: https://salahealer9.github.io/sri-yantra-spherical-viewer/
- E8 globe interactive research viewer: https://salahealer9.github.io/e8-globe-viewer/

These external viewers are separate projects. The website includes links, not copies of their code or data.
