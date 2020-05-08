# nuxt-boilerplate

> Pulsar nuxt PWA GraphQL boilerplate

## Plugins

- `@nuxtjs/svg-sprite`
- `@nuxtjs/apollo`
- `@nuxtjs/dotenv`
- `@nuxtjs/pwa`

### Developement

- `@nuxtjs/style-resources`
- `sass-loader`
- `node-sass`

### Visual Studio Code

- `kumar-harsh.graphql-for-vscode`
- `dbaeumer.vscode-eslint`
- `prisma.vscode-graphql`
- `mrmlnc.vscode-scss`
- `octref.vetur`

## Environment variables

- `DEFAULT_ENDPOINT` ('' by default) GraphQL endpoint url
- `SENTRY_DSN` (undefined by default) Sentry DSN

## Configuration

Style can be configured via [main.scss](assets/scss/main.scss) variables.

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at 0.0.0.0:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
