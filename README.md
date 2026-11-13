# Yuan Yuan — CV

This repository hosts my CVs as PDFs using GitHub Pages.

The homepage opens `cv.pdf` directly. If automatic navigation is unavailable, it provides a link to the PDF.

## Updating the CV

The CV is maintained in Overleaf. After reviewing a change, use **Integrations → GitHub → Push Overleaf changes to GitHub**. A build in the private source repository updates only `cv.pdf` here, then GitHub Pages publishes the website at the same address.

The LaTeX source and build logs remain private. This repository contains the public PDF and website configuration only.

As a manual fallback, replace `cv.pdf` with a newly exported PDF, then commit and push to `main`.

## Hosting

The public website is [lmgyuan.github.io/cv](https://lmgyuan.github.io/cv/).

In **Settings → Pages**, the source is **GitHub Actions**. The publishing workflow packages both CV PDFs and their website entry points. The Generative 3D / World Model / Robotics version is at [lmgyuan.github.io/cv/3d](https://lmgyuan.github.io/cv/3d/).
