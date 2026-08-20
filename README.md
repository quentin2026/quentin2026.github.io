# Guanting Liu - Academic Homepage

This is a static website designed for GitHub Pages. `index.html` is the entry point and `CV.pdf` is linked directly from the navigation and CV section.

## Publish at GitHub Pages

1. Create a public GitHub repository named `<your-github-username>.github.io`.
2. Upload this folder's contents to the repository root, keeping `index.html`, `style.css`, `CV.pdf`, and `证件照.png` together.
3. In the repository's **Settings > Pages**, set the deployment source to **Deploy from a branch**, then select the `main` branch and the `/ (root)` folder.
4. The site will be available at `https://<your-github-username>.github.io` after GitHub finishes deploying it.

## Adding Research Images

The Research section currently uses deliberately styled placeholders. Add wide project figures (at least a 3:2 aspect ratio) to `assets/research/` with these exact names; each image will automatically replace its matching placeholder after the next GitHub push:

- `task-driven-brain-modelling.jpg`
- `cognitive-modelling.jpg`
- `model-organism-simulation.jpg`
- `invasive-bci-decoding.jpg`
- `eeg-decoding.jpg`
