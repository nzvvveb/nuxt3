# Nuxt 3 Minimal Starter

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install
```

## Development Server

Start the development server on `http://localhost:3000`

```bash
pnpm run dev
```

## Production

Build the application for production:

```bash
pnpm run build
```

Locally preview production build: (not available with aws-lambda preset)

```bash
pnpm run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
## deploy to AWS Serverless
install [serverless framework](https://www.serverless.com/framework/docs/getting-started)

```bash
pnpm run package
pnpm run deploy
```


