# Guanting Liu - Academic Homepage

This is a static website designed for GitHub Pages. `index.html` is the entry point and `CV.pdf` is linked directly from the navigation and CV section.

## Publish at GitHub Pages

1. Create a public GitHub repository named `<your-github-username>.github.io`.
2. Upload this folder's contents to the repository root, keeping `index.html`, `style.css`, `CV.pdf`, and `证件照.png` together.
3. In the repository's **Settings > Pages**, set the deployment source to **Deploy from a branch**, then select the `main` branch and the `/ (root)` folder.
4. The site will be available at `https://<your-github-username>.github.io` after GitHub finishes deploying it.

## Adding Research Images

The Research section currently uses deliberately styled placeholders. When project figures are ready, replace each corresponding `.research-visual` block in `index.html` with an `<img>` element and store the image files in an `assets/research/` folder. Use wide images with at least a 3:2 aspect ratio for the current layout.

