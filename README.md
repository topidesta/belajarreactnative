[![Netlify Status](https://api.netlify.com/api/v1/badges/24676106-bd9b-4de8-8390-e526e2495ae4/deploy-status)](https://app.netlify.com/sites/belajarreactnative/deploys)

# Website

Belajar ReactNative dibuat dengan [Docusaurus 2](https://v2.docusaurus.io/)

### Installation

```
$ yarn
$ yarn start
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

```
$ GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

### Searching Build

```
$ yarn build
$ node build-search-data.js
```

Update your index of searching using lunr.js!

### Netlify

```
https://belajarreactnative.netlify.app/
```
