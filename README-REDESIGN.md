# Naithani Lab website redesign

Inspired by the information hierarchy of esiil.org, not a reproduction.

## Install
Copy the files and directories into your GitHub Pages repository, preserving your existing `docs/images/` content. `docs/images/banner.png` and `docs/images/lab-logo.png` are included.

In RStudio, open the project and run `rmarkdown::render_site()` from the repository root. Commit the resulting `docs/` site output.

**Note:** This ZIP includes the supplied Rmd pages and new homepage/style/banner, but not your other original `docs/images` assets. Keep those existing files in your repository. The provided `docs/assets/style.css` is a convenience copy; the build uses `assets/style.css` as configured in `_site.yml`.

The banner is AI-generated and its embedded logo lettering may not exactly match the supplied original; `docs/images/lab-logo.png` is the unmodified supplied logo for future use.
