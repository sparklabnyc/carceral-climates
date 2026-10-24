# Carceral Climates

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="/logo-dark.svg">
    <img src="/logo-light.svg" alt="Carceral Climates" width="600">
  </picture>
</p>

Official website repository for **Carceral Climates**: data and solutions for the impacts of climate-related extremes on incarcerated people in the United States.

🌐 Live site:
https://www.carceralclimates.org

Funded by Wellcome.

---

## Overview

This repository hosts the static website deployed via **GitHub Pages** and served at the custom domain above.

---

## Repository Structure

```
.
├── index.html          # Main website page
├── CNAME               # Custom domain configuration for GitHub Pages
├── README.md           # Repository documentation
│
├── logo-light.svg      # Logo for light backgrounds
├── logo-dark.svg       # Logo for dark backgrounds
│
├── favicon.ico         # Browser favicon
├── favicon.svg         # Scalable favicon
├── favicon-96x96.png   # PNG favicon fallback
├── apple-touch-icon.png
├── web-app-manifest-192x192.png
├── web-app-manifest-512x512.png
├── site.webmanifest    # Web app manifest
```

---

## Deployment

The site is deployed automatically through **GitHub Pages**.

Hosting stack:

* Static HTML
* GitHub Pages
* Custom domain via DNS
* HTTPS via GitHub SSL

Updates pushed to the repository will automatically redeploy the site.
