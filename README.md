# Parcel Landing Page Example

Note: in 2024, I'd recommend using [Astro](https://astro.build/) for simple landing pages instead of this, but if you don't have a couple of hours to learn Astro, then this still works.

Features:

- Use TypeScript or JavaScript
- Use SCSS or CSS
- Quickly include Google Fonts
- Runs tasks on staged files automatically (formatting, etc.)
- Optionally deploy to a staging environment
- Deploys production build to [Cloudflare Pages](https://pages.cloudflare.com/) (free)

See the `package.json` file for a list of available scripts.

First, install `yarn` if you don't have it:

```text
npm i -g yarn
```

Then install dependencies and run the local server at `http://localhost:1234`:

```text
yarn
yarn start
```

When ready to deploy, create a [Cloudflare](https://cloudflare.com/) account and log in via the terminal:

```text
wrangler login
```

To deploy after that, run this command:

```text
yarn deploy
```

You can then set up a custom domain or other settings in the Cloudflare Pages dashboard.

[Live demo](https://parcel-landing-page.pages.dev/)
