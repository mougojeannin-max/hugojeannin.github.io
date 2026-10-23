# Hugo Jeannin’s personal website

A static page in English, ready to upload to GitHub Pages. No build tools or dependencies are required.

## Preview

Open `index.html` in a browser. The page and its local links work directly from this folder.

## Publish on GitHub Pages

1. Open the public repository **[mougojeannin-max/site](https://github.com/mougojeannin-max/site)**.
2. Upload **the contents of this folder** to the repository root: `index.html`, `style.css`, `favicon.svg`, `.nojekyll` and the `assets` folder. Extract the ZIP first; do not upload the ZIP itself or nest the `site-web` folder inside the repository.
3. Under **Settings → Pages**, select **Deploy from a branch**, then **main** and **/ (root)**. Save.
4. The page will be available at **https://mougojeannin-max.github.io/site/** once GitHub finishes deploying, which may take a few minutes.

The `.nojekyll` file is included to serve static files directly. If it does not appear in the upload interface, the HTML page also works without it.

Official documentation: [GitHub Pages quickstart](https://docs.github.com/en/pages/quickstart).

## Edit the website

- Text, publications and links: `index.html`.
- Colours, typography and layout: `style.css`.
- Photo: `assets/hugo-jeannin.jpg` (the supplied photo, unchanged).
- Downloadable CV: `assets/Hugo_Jeannin_CV.pdf`. Replace this file while keeping the same name when updating the CV.

The downloadable CV is a copy of the existing English CV supplied in the project. The original LaTeX sources and PDF are unchanged.

The manuscript *Pooled Covariance Whitening and Random Matrix-Corrected Grassmann Distance for Spiked Covariance Classification* is listed as under review; the supplied CV does not include a public link.

## Links

- Supplied GitHub profile: https://github.com/mougojeannin-max
- LinkedIn profile matched using the name and academic background: https://www.linkedin.com/in/hjeannin/
- RMT preprint: https://arxiv.org/abs/2610.18059
- TMLR paper: https://arxiv.org/abs/2404.02314
- EUSIPCO paper: https://doi.org/10.23919/EUSIPCO63237.2025.11226606
- EUSIPCO PDF in the conference proceedings: https://www.eurasip.org/Proceedings/Eusipco/Eusipco2025/pdfs/0002597.pdf

The page uses only local files for its appearance: no external fonts, scripts or analytics.
