# Personal Website

[![Open in Visual Studio Code](https://open.vscode.dev/badges/open-in-vscode.svg)](https://open.vscode.dev/mitchellolsthoorn/personal-website)

[![Netlify Status](https://api.netlify.com/api/v1/badges/ff9f6e08-d300-4f53-9695-a42bd08adf57/deploy-status)](https://app.netlify.com/sites/mitchellolsthoorn/deploys)
![Security Headers](https://img.shields.io/security-headers?url=https%3A%2F%2Fwww.mitchellolsthoorn.com)
![Website](https://img.shields.io/website?url=https%3A%2F%2Fwww.mitchellolsthoorn.com)

This repo contains the sources for my personal website.
The website uses the open-source static site generator [Hugo](https://gohugo.io/) for building the website.
It is based on the [Wowchemy](https://wowchemy.com/) theme and is hosted on [Netlify](https://www.netlify.com/).

## Build and preview locally

When making changes to the website, it is useful to build and preview the website locally before committing the changes to the repository.
Before you can build the website, you first need to install the following dependencies:

1. Install Hugo using [this documentation](https://gohugo.io/getting-started/installing/).
2. Install NPM using [this documentation](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
3. Install the development dependencies: `npm install`

To preview the website:

1. Run `view.sh`

When making changes, format the files afterwards:

1. Run `npm run format`

When an error occurs during building, try deleting the local Hugo cache:

- MacOS/Linux: `sudo rm -rf $TMPDIR/hugo_cache/`

## Deploy website

The website is automatically deployed whenever a new commit is merged into the main branch.
To see a preview of the changes in a PR, press the details link in the deploy status check.

## License

The content of this project itself is licensed under the [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1), and the underlying source code used to format and display that content is licensed under the [MIT license](LICENSE.md).
