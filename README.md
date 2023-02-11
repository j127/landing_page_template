# Parcel Landing Page Example

Features:

- Use TypeScript or JavaScript
- Use SCSS or CSS
- Quickly include Google Fonts
- Runs tasks on staged files automatically (formatting, etc.)
- Optionally deploy to a staging environment
- Deploys production build to Netlify (free)

See the `package.json` file for a list of available scripts.

```text
yarn
yarn start
```

When ready to deploy, get your Netlify credentials ready and run these commands once:

```text
yarn netlify:login
yarn netlify:link
```

You won't have to run those again. To deploy after that, run this command:

```text
yarn deploy
```
