# Enforcing localhost to run into https

## Setup to enable https on localhost in a basic Next JS webapp

#### ***Branch name -*** [basic-next-js-webapp-on-https](https://github.com/drcount-root/enforcing-https-in-localhost/tree/basic-next-js-webapp-on-https)

1. ***Update to latest Next.js via:*** `npm i next@latest react@latest react-dom@latest eslint-config-next@latest`
2. ***Update package.json script for "dev" to:*** `next dev --experimental-https`

---

## Setup to enable https on localhost in any app inside basic Turborepo (Monorepo) apps

#### ***Branch name -*** [basic-turborepo-monorepo-webapps-on-https](https://github.com/drcount-root/enforcing-https-in-localhost/tree/basic-turborepo-monorepo-webapps-on-https?tab=readme-ov-file)

1. Update package.json script for "dev" into the app which you want, inside apps folder to: `next dev --experimental-https`.