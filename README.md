# Zeller1 Static Site

This repository contains a static HTML site.

## Deploying to Render

1. Log in to [Render](https://render.com) and create a new **Static Site**.
2. Connect this repository and use the following settings:
   - **Build Command:** leave blank
   - **Publish Directory:** `.`
3. Save the site and Render will deploy the contents of the repository so that `index.html` is served at the root.

The `render.yaml` file in this repo contains the same configuration and allows Render to auto-detect the static site.
