# A Star Cleaning Specialists – example website

Static one-page site (plain HTML/CSS, no build step) for an exterior jet wash, roof cleaning and minor gutter repair business covering Manchester and surrounding areas. Blue and white branding; logo in `images/logo.jpg`.

## Publishing
In the repo go to Settings → Pages → Source: "GitHub Actions". Pushing to `main` deploys the site via `.github/workflows/pages.yml` (no build step needed; all paths are relative so it works under `/Astar/`).

## To replace
- Phone, email, Facebook/Instagram links (`href="#"` placeholders) and certificate/insurance details in `index.html`.
- Service tiles (`.ph` placeholders) and "Our work" gallery with real photos: add to `images/` and swap each `.ph` div for an `<img>`.
