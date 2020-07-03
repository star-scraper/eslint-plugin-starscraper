# eslint-config-starscraper

The standard guide to convention for Starscraper projects

## Getting Started

Install the package

`$ npm install eslint-plugin-starscraper`

## Using the rule(s)

Add the plugin to the list of plugins in the .eslintrc file

```
{
  -----------
  "plugins": [
    "starscraper"
  ],
  --------------
}
```

Add to rule(s)

```
{
  -----------
  "rules": {
    "starscraper/test-id-match": "error",
    "starscraper/intl-id-match": "error",
     "starscraper/validate-unique-test-intl-id": "error",
  },
  --------------
}
```
