VSC plugins:

- Prettier - Code formatter
- ESLint

In Evry New Project Directory:

```sh
npm init -y
npm i eslint -D
npx eslint --init
```

1. select **"Use a popular style guide"**
2. **Airbnb**
3. Do you use React? **N**
4. What format do you want your config file to be in? **JavaScript**
5. What do you like to install them now with npm? **Y**

add to .eslintrc.js

```js
,
  rules: {
    'no-console': 'off',
  },
```

```sh
npm i prettier eslint-plugin-prettier -D
npm i eslint-config-prettier -D
```

### VSC Setting

- for Prettier

```json
VSC settings: "prettier.eslintIntegration": true.
```

- for ESLinter

```json
"editor.formatOnSave": true,
"eslint.autoFixOnSave": true,
"eslint.alwaysShowStatus": true,
"files.autoSave": "onFocusChange",
"eslint.packageManager": "npm",
"prettier.eslintIntegration": true
```
