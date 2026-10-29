# James Blackwell — personal website

A buildless, three-page website for GitHub Pages. No dependencies or build command.

## Upload and publish
1. Unzip this archive.
2. Open the personal-website repository on GitHub.
3. Use Add file → Upload files. Upload the CONTENTS of this folder, keeping assets/, research/ and teaching/ as folders. index.html must be at the repository root.
4. Commit changes.
5. In Settings → Pages choose Deploy from a branch, main, /(root), then Save.
6. Open https://jamesblackwell-ie.github.io/personal-website/ after deployment completes.

## Editing
- index.html: home and biography.
- research/index.html: research overview.
- teaching/index.html: teaching page and simulation collection link.
- assets/site.css: shared colours, typography and responsive layout.
- assets/waves.svg: abstract decorative wave illustration.

The simulation collection stays at https://jamesblackwell-ie.github.io/map-physics-lab/. No files or settings in that repository need to change.

All internal links are relative, so the site works at the GitHub project address and at a custom domain. No CNAME is included: connect jblackwell.ie in Pages settings only once domain registration and DNS setup are ready.

This is a first draft based on the supplied background. Review biography wording before publishing. The supplied portrait, Google Scholar and ORCID links are included. Publications are linked through Google Scholar.

## Publications
publications/index.html lists the 11 supplied papers, grouped by publication year. Original PDF bytes are preserved under publications/pdfs/ with simple filenames. Citation data are in publications/citations.json. Upload the entire publications folder along with the updated pages and assets. The separate single-file preview embeds PDFs for offline downloads; do not upload that preview as the website index.
