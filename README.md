# Wren M. Burton — portfolio

A lightweight, responsive portfolio built with plain HTML, CSS, and JavaScript. No build step or dependencies are required.

## Preview locally

Open `index.html` in a browser, or run a local static server from this directory:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a GitHub repository for the site (a user site is named `<username>.github.io`; a project site can use any repository name).
2. Add these files to the repository and push them to GitHub.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select the branch containing `index.html` and the `/ (root)` folder, then save.
5. GitHub Pages will show the published URL in the Pages settings.

## Personalize

Update the draft copy and content prompts in `index.html`. Replace the CV placeholder with a link to a PDF, and add an email address and professional profile links when ready. The site uses Google Fonts when a network connection is available and falls back to system fonts otherwise.
