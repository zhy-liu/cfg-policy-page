# CFG-Policy project page

A static project page for **CFG-Policy: Unified Diffusion Policy Learning Framework via Classifier-free Guidance**, based on the manuscript in the supplied ZIP archive. The page follows the title → overview → method → results structure of the [QVPO project page](https://github.com/wadx2019/qvpo-webpage), with original HTML/CSS and figures rendered from the CFG-Policy manuscript.

## Preview locally

Open `index.html` in a browser, or serve the directory with any static web server. There is no build step or runtime dependency.

## Content notes

- The manuscript's `\author{}` field contains template placeholder names, so the page intentionally does not publish author names or a citation.
- A public paper PDF and implementation repository were not present in the supplied materials; resource links can be added when those are available.
- Result tables reproduce values from the manuscript. The figures in `assets/` were rendered from its PDF figures.

## GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the repository root as a static GitHub Pages site. In the repository's **Settings → Pages**, choose **GitHub Actions** as the build and deployment source. The intended URL is `https://zhy-liu.github.io/cfg-policy-page/`.
