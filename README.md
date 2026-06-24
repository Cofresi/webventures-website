# Web Ventures GmbH Static Website

A lightweight one-page static website for [Web Ventures GmbH](https://webventures.ch), built with plain HTML, CSS and minimal vanilla JavaScript. It is designed to run locally by opening `index.html` and to deploy directly to GitHub Pages.

## Preview Locally

Open `index.html` in a browser. No build step, package manager, server or framework is required.

## Deploy With GitHub Pages

1. Commit `index.html`, `styles.css`, `script.js` and `README.md` to a GitHub repository.
2. In the repository settings, open **Pages**.
3. Choose the branch that contains these files, usually `main`.
4. Select the repository root as the publishing source.
5. Save the settings and wait for GitHub Pages to publish the site.

## Replace the Email Address

The contact button in `index.html` currently uses the placeholder address:

```html
mailto:hello@webventures.ch
```

Replace it with the real launch email address before publishing. There is an HTML comment near the link marking the exact location.

## Edit Company Copy

Most visible company copy is in `index.html`. The visual styling is in `styles.css`, and the mobile menu, current footer year and subtle reveal effects are handled in `script.js`.

## Connect a Custom Domain Later

After GitHub Pages is enabled, add the desired domain in the GitHub Pages settings. Then configure the domain provider's DNS records according to GitHub's current Pages documentation. If using an apex domain, GitHub also supports adding a `CNAME` file or using the Pages settings UI to create one.

## Legal and Privacy Text

The footer contains placeholder Privacy and Legal Notice links. Replace these with proper legal and privacy content before launch. No legal registration details, addresses or contact information have been invented in this version.
