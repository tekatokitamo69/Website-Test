# For Hanhan, with love

A birthday gift for Hanhan, from Botoy, for November 3. A responsive static website with a birthday cake illustration, an interactive love letter, and a wish celebration. No build step or package installation is required.

## Run locally

From this directory:

```sh
python3 -m http.server 3000 --bind 0.0.0.0
```

## Personalize

Edit the text in `index.html`, especially the love letter in `#love-letter` and the three reason cards. Names and date are included directly in the HTML. Google Fonts is optional; the site falls back to local serif and sans-serif fonts when offline. No analytics or data collection.

## Publish with GitHub Pages

Push these files to the `main` branch of your GitHub repository. Under **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save. GitHub will show the public site address once deployment finishes.
