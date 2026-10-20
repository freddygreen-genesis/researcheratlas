# Researcher Atlas — GitHub Pages edition

This folder is the ready-to-publish website. No installation or build is needed.

## Publish using GitHub

1. Create a GitHub repository (a public repository is the simplest option).
2. Unzip the download. In the repository, choose Add file → Upload files. Drag the CONTENTS of this folder into GitHub, including the assets folder. Do not upload the ZIP itself or put everything inside another folder. Commit the files to the main branch. index.html must appear at the top level of the repository.
3. Open Settings → Pages. Under Build and deployment, set Source to Deploy from a branch. Choose main and /(root), then Save.
4. Wait for GitHub to finish deployment. The Pages settings will show the website link; share that link with colleagues.

The hidden .nojekyll file is included. If your upload omits it, this bundle uses ordinary asset names and does not need Jekyll processing.

## Using the app

Enter your own OpenAlex API key in the app and select Save key. The key is stored in this browser and sent only to OpenAlex for API requests. Never add an API key to this repository. Each colleague should use their own key.

Saved explorations and keys remain local to the browser, rather than syncing between people or devices. Saved explorations from the old localhost address will not automatically appear at the new GitHub address.

The website runs entirely in the browser and contacts OpenAlex directly. Your computer does not need to stay on. Internet access and available OpenAlex quota are required. Standard GitHub Pages sites are public-facing; a private repository does not by itself make its Pages site private.

Coauthors are ranked by shared publications. Recorded affiliations are derived from publications, not verified employment history.

## Updating

Upload a new build's index.html and assets together and commit. Keep the same repository address to retain browser-local saved explorations.

GitHub instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
