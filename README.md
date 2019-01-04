# eslint-plugin-wepy

eslint plugin for wepy file

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `@setstate/eslint-plugin-wepy`:

```
$ npm install @setstate/eslint-plugin-wepy --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `@setstate/eslint-plugin-wepy` globally.

## Usage

Add `wepy` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "@setstate/wepy"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "@setstate/wepy/script-indent": ['warn', 2, {
          'baseIndent': 1,
        }]
    }
}
```

## Supported Rules

### [@setstate/wepy/script-indent](https://github.com/ineo6/eslint-plugin-wepy/blob/master/docs/rules/script-indent.md)

This rule is similar to core [indent](https://eslint.org/docs/rules/indent) rule, but it has an option for inside of <script> tag.






