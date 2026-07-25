# Jianing Xie — Academic Homepage

A lightweight academic homepage adapted from the visual structure of [Jon Barron's website](https://jonbarron.info/) and the public source repository [`jonbarron/jonbarron.github.io`](https://github.com/jonbarron/jonbarron.github.io).

## Before publishing

Search the files for these placeholders and replace them:

- `YOUR_EMAIL`
- `YOUR_GITHUB_USERNAME`
- `YOUR_LINKEDIN_HANDLE`

Replace `images/profile-placeholder.svg` with your own portrait, for example `images/profile.jpg`, and update the image path in `index.html`.

Review every research description and date before making the site public. The current copy is a polished draft based on your existing project information, not an official CV record.

## Publish with GitHub Pages

1. Create a GitHub repository named `<your-username>.github.io`.
2. Upload everything in this folder to the repository root.
3. Commit and push to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select `main` and `/(root)`, then save.
7. Your site should appear at `https://<your-username>.github.io/` after deployment completes.

## Preview locally

From this directory, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Main files

- `index.html` — homepage content
- `cv.html` — web CV draft
- `stylesheet.css` — shared styling
- `images/` — portrait placeholder and project illustrations

## Notes

This is plain HTML/CSS; there is no build step and no package installation. The `.nojekyll` file tells GitHub Pages to serve the files directly.
