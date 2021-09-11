# @theonlydevsever/eslint-config

![publish](https://github.com/theonlydevsever/eslint-config/actions/workflows/publish.yml/badge.svg)
![tag](https://github.com/theonlydevsever/eslint-config/actions/workflows/tag.yml/badge.svg)

[ESLint](https://eslint.org/) configuration for [@theonlydevsever](https://github.com/theonlydevsever)

## Install

```
// using yarn
yarn add -D @theonlydevsever/eslint-config eslint eslint-config-prettier eslint-plugin-html eslint-plugin-import eslint-plugin-jest eslint-plugin-jest-extended eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks prettier @typescript-eslint/eslint-plugin @typescript-eslint/parser

// using npm
npm install --save-dev @theonlydevsever/eslint-config eslint eslint-config-prettier eslint-plugin-html eslint-plugin-import eslint-plugin-jest eslint-plugin-jest-extended eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks prettier @typescript-eslint/eslint-plugin @typescript-eslint/parser
```

## Usage

This configuration can be set up using the `package.json` or `.eslintrc` file.

### package.json

```json
{
    "name": "side-walk-when-she-walks",
    "version": "1.0.0",
    "author": "alexisonfire",
    "eslintConfig": {
        "extends": ["@theonlydevsever"]
    },
    "dependencies": {
        "react": "^17.0.1"
    }
}
```

### .eslintrc

```js
{
    "extends": ["@theonlydevsever"]
}
```

## Ignoring Files

If you want eslint to ignore certain files, create a `.eslintignore` file in your project's root firectory and add all of the files you want eslint to ignore.

Here is our recommended `.eslintignore`

```
build
coverage
*.db
*.log
*.lock
*.json
docs
node_modules
public
prettier.config.js
```
