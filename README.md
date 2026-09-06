# fdc-catalog

`catalog.json` is the single source of truth for everything Fusion Data Company sells.
fusiondataco.com renders its product pages from the raw file:

    https://raw.githubusercontent.com/Fusion-Data-Company/fdc-catalog/main/catalog.json

Rules: each entry has an `owner`; only that owner edits it. Prices here are the only
published prices. `status` is `live` (a stranger can pay and receive), `demo` (public
demo, no checkout yet) or `soon`. Bump `updated_at` on every change.
