# Jingyi Lan personal homepage

A clean static academic homepage prepared for GitHub Pages.

## Files

- `index.html`: homepage content and link placeholders
- `styles.css`: visual design
- `assets/`: put downloadable files and images here
- `.nojekyll`: tells GitHub Pages to serve files directly without Jekyll processing

## Add your profile photo

Save your photo as:

```text
assets/profile.jpg
```

Recommended photo format:

```text
square image, at least 800 × 800 px
```

If your image has another filename, update this line in `index.html`:

```html
<img src="assets/profile.jpg" alt="Portrait of Jingyi Lan" />
```

For example:

```html
<img src="assets/jingyi-lan.jpg" alt="Portrait of Jingyi Lan" />
```

## How to edit links

In `index.html`, search for `href="#"` and replace `#` with the actual URL.

Examples:

```html
<a href="https://scholar.google.com/citations?user=YOUR_ID">Google Scholar</a>
<a href="https://github.com/YOUR_USERNAME">GitHub</a>
<a href="https://example.com/paper.pdf">Paper</a>
<a href="https://github.com/YOUR_USERNAME/YOUR_REPO">Code</a>
<a href="assets/bibtex/paper-name.bib">BibTeX</a>
```

To add your CV, export your CV as a PDF and save it as:

```text
assets/Jingyi_Lan_CV.pdf
```

## GitHub Pages deployment

1. Create a GitHub repository named `<your-github-username>.github.io`.
2. Upload `index.html`, `styles.css`, `.nojekyll`, and the `assets/` folder to the repository root.
3. Go to `Settings` → `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Choose `main` and `/root`, then save.
6. Visit `https://<your-github-username>.github.io` after GitHub finishes deployment.
