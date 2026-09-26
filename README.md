# UNA-USA Akron website

This repository publishes the University of Akron UNA-USA chapter site to GitHub Pages. The expected address is https://una-usa-akron.github.io/ when the repository belongs to the `UNA-USA-Akron` organization and is named `UNA-USA-Akron.github.io`.

To update content, edit `build.py` or files in `assets/`, commit to `main`, and the workflow builds and publishes `dist/`. The `dist/` directory is included so the site can also be reviewed before the first workflow runs.

In repository **Settings → Pages → Build and deployment**, select **GitHub Actions** as the source. GitHub Pages must be enabled for this public repository. Do not enter visitor responses or private member data into this repository.
