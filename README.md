# eslint-config-spatie

Our base eslint configuration.

Spatie is a webdesign agency based in Antwerp, Belgium. You'll find an overview of all our open source projects [on our website](https://spatie.be/opensource).

## Installation

Install this package, and save it as a devDependency:

```
npm install --save-dev eslint-config-spatie
```

Then have your project's `.eslintrc` file extend the ruleset.

```json
{
    "extends": "spatie"
}
```

If you're using React in your project, you'll need to extend the React extension of the configuration, and install the eslint React plugin:

```json
{
    "extends": "spatie/react"
}
```

```
yarn add eslint-plugin-react --dev
```

If you're using Vue in your project, you'll need to extend the Vue extension of the configuration, and install the eslint Vue and html plugins:

```json
{
    "extends": "spatie/vue"
}
```

```
yarn add eslint-plugin-vue eslint-plugin-html --dev
```

## Common Settings Cookbook

### Globals

```json
{
    "globals": {
        "$": true
    }
}
```

### Environments

```json
{
    "env": {
      "browser": true,
      "node": true
    }
}
```

## About Spatie

Spatie is a webdesign agency based in Antwerp, Belgium. You'll find an overview of all our open source projects [on our website](https://spatie.be/opensource).

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
