[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)
[![Netlify Status](https://api.netlify.com/api/v1/badges/4d494950-1c5d-49c7-976c-229f166d02d1/deploy-status)](https://app.netlify.com/sites/priceless-visvesvaraya-089d7a/deploys)

# Netlify CMS sandbox

This is proof of concept for a website using [Netlify CMS][netlify-cms] with [Next][next].

The idea behind it is to reduce dependencies, infrastructure configuration and identity managament for the CMS to the integration that Netlify already have with

- GitHub
- Azure (active directory)
- Or another [OAuth clients](oauth-clients)

[netlify-cms]: https://www.netlifycms.org/docs/intro/
[next]: https://nextjs.org/
[oauth-clients]: https://www.netlifycms.org/docs/external-oauth-clients/

The CMS persitant storage is your remote repo, in this case https://github.com/redbadger/netlify-cms-sandbox

## Production build

The website is published on https://priceless-visvesvaraya-089d7a.netlify.app/

## CMS access

To get access to the CMS do the following:

- Send a message or email to [Pedro][pedro] to add you as an editor with the email associated to you GitHub account.

- Once you receive the invation email go to the [CMS admin page][cms-admin]

[pedro]: mailto:pedro.martin@red-badger.com
[cms-admin]: https://priceless-visvesvaraya-089d7a.netlify.app/admin

## Installation

- Download this repo

```sh
git clone git@github.com:redbadger/netlify-cms-sandbox.git
```

- Install dependencies

```sh
yarn
```

- Have fun
