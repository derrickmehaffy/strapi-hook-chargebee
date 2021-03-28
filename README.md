# strapi-hook-chargebee

<a href="https://www.npmjs.org/package/strapi-hook-chargebee">
    <img src="https://img.shields.io/npm/v/strapi-hook-chargebee" alt="NPM Version" />
</a>
<a href="https://www.npmjs.org/package/strapi-hook-chargebee">
    <img src="https://img.shields.io/npm/dm/strapi-hook-chargebee.svg" alt="Monthly download on NPM" />
</a>

## This hook is a WIP and is not production ready!

This hook allows you to use [Chargebee](https://www.chargebee.com/) as a service in [Strapi](https://github.com/strapi/strapi) `strapi.services.chargebee`. Chargebee is a subscription billing and revenue operations system for B2B style transactions, it can be used to process payments and handle subscription-like transactions.

**Supported Strapi versions:**

- v3.5.x (recommended)
- v3.x

_Older version may work with the beta version of this hook, but are not supported._

## Installation

```bash
# using yarn
yarn add strapi-hook-chargebee

# using npm
npm install strapi-hook-chargebee --save
```

## Usage

**WIP**

## Hook config

To activate and configure the hook, you need to create or update the file `./config/hook.js` in your strapi app.

```js
module.exports = {
  settings: {
    // ...
    chargebee: {
      enabled: true,
    },
  },
};
```

### Support

- [Strapi community on Slack](https://slack.strapi.io) for general chatting or questions
- [GitHub issues](https://github.com/derrickmehaffy/strapi-hook-chargebee/issues) for Bugs and Feature requests

### Resources

- [Strapi website](http://strapi.io/)
- [Strapi forum](https://forum.strapi.io/)
- [Strapi news on Twitter](https://twitter.com/strapijs)

### License

- Copyright (c) 2020-2021 Derrick Mehaffy & Strapi Solutions ([GPLv3 License](LICENSE.md)).
