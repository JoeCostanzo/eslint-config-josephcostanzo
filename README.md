# eslint-config-josephcostanzo

Joseph Costanzo’s config for [ESLint](http://eslint.org/)

## Installation
```
npm i --save-dev eslint eslint-config-josephcostanzo
```

## Usage
Add the following entry to your `.eslintrc`
```json
{
  "extends": "josephcostanzo"
}
```

It's easiest to add a script to `package.json` to run linting; for example,
```json
{
  "scripts": {
    "lint": "eslint <path_to_javascript_dir>"
  }
}
```

Then just `$ npm run lint`
