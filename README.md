# UX Wizard Spellbook

[![Netlify Status](https://api.netlify.com/api/v1/badges/91850b15-3d0c-4a09-81f8-57dda1d3258c/deploy-status)](https://app.netlify.com/sites/uxwizardswiki/deploys)

## Formatting

We will be using Prettier to format document changes.

## Code style guide

1. root level `index.md` is where the wiki will open to.
1. `position` property indexes start at 1.
1. File names are in [kebab-case](https://en.wikipedia.org/wiki/Letter_case#Special_case_styles). `title` property are sentence case versions of that file name.
1. Put markdown files within their respective `category` directory.
1. Category titles should be descriptive. Consider adding a new file to an existing category before creating a new one.
1. WIP: Where to put images.

## Setup

Install dependencies:

```bash
yarn install
```

## Development

```bash
yarn dev
```

## Static Generation

This will create the `dist/` directory for publishing to static hosting:

```bash
yarn generate
```

To preview the static generated app, run `yarn start`

For detailed explanation on how things work, checkout [nuxt/content](https://content.nuxtjs.org) and [@nuxt/content theme docs](https://content.nuxtjs.org/themes-docs).
