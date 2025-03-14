# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator, and [Tina](https://tina.io), a git-backed headless Content Management System (CMS).


[![Netlify Status](https://api.netlify.com/api/v1/badges/d49f6c03-36b2-4f16-b8f0-63b9a33934f8/deploy-status)](https://app.netlify.com/sites/chen-cms/deploys)

### Installation

```
$ pnpm
```

### Local Development

```
$ pnpm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ pnpm build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true pnpm deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> pnpm deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
