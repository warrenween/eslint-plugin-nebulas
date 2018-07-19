# eslint-plugin-nebulas

smart contract lint rules

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-nebulas`:

```
$ npm install eslint-plugin-nebulas --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-nebulas` globally.

## Usage

Add `nebulas` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "nebulas"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "nebulas/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





