# VD Landscape Pros Website

Static HTML/CSS/JS website for GitHub Pages.

## Upload structure

Upload these files to the repository root:

```text
.nojekyll
CNAME
index.html
services.html
portfolio.html
contact.html
styles.css
script.js
README.md
assets/
  images/
    hero-paver-patio-firepit.jpg
    curved-backyard-paver-patio.jpg
    firepit-seating-wall-walkway.jpg
    geometric-paver-patio.jpg
    gray-paver-patio-steps.jpg
    firepit-seat-wall-patio.jpg
    front-paver-walkway.jpg
    covered-porch-paver-walkway.jpg
    large-curved-paver-patio.jpg
```

## GitHub Pages

1. Go to repository Settings.
2. Click Pages.
3. Source: Deploy from a branch.
4. Branch: main.
5. Folder: /root.
6. Save.

## Custom domain

In GitHub Pages custom domain, use:

```text
vdlandscapepros.com
```

DNS records:

A records for `@`:

```text
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

CNAME for `www`:

```text
yourgithubusername.github.io
```

After DNS validates, enable HTTPS.
