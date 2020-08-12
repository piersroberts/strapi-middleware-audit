# strapi-middleware-audit

> Logs's all authenticaticated requests to Strapi's admin

---

## Installation

Install with `yarn add strapi-middleware-audit`

Enable the middleware by editting your `config/middleware.js` file (create it if isn't there already), it should look like this,

```
module.exports = {
  settings: {
    audit: {
      enabled: true,
    },
  },
}
```

That's it! When you use the admin interface, you should start seeing things appear in your Strapi logs

## Contributing

Patches welcome! If you do find any issues please raise an issue on github https://github.com/piersroberts/strapi-middleware-audit/issues
