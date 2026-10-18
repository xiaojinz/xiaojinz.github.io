# EMERGE Academic Website

Academic Pages theme: https://github.com/academicpages/academicpages.github.io

This website uses the Academic Pages upstream theme via `jekyll-remote-theme` (not a custom redesign). It is configured for `xiaojinz.github.io`.

To edit:
- `_pages/home.md`, `team.md`, `research.md`, `publications.md`, `openings.md`, `gallery.md`: page text.
- `_data/navigation.yml`: top tabs.
- `_config.yml`: site metadata and sidebar.
- `assets/css/main.scss`: unmodified Academic Pages SCSS imports.

**Review before publishing:** Member titles, paper review status, Ph.D. opening availability, and image assets. Original source: https://sites.google.com/view/xjzheng/home

**Photo migration:** The Gallery currently includes all captions but not the original Google Sites photo files. Download photos with permission and upload to `images/` for self-hosting; avoid relying on Google-hosted images for mainland China visitors.

**Deployment:** Merge into `main` once reviewed, then in Settings → Pages choose `Deploy from a branch`, `main`, `/(root)` and save. If Pages was previously set to website-v1, change to main after the merge. GitHub Pages/Jekyll remote theme support must be enabled.
