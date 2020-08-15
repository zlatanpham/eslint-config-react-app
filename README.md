# eslint-config-react-app

This package includes the shareable ESLint configuration extended by [eslint-config-react-app](https://github.com/facebook/create-react-app/tree/master/packages/eslint-config-react-app).<br>
Please refer to its documentation:

## Usage

First, install this package, ESLint and the necessary plugins.

```sh
npm install --save-dev @@zlph/eslint-config-react-app eslint-config-react-app @typescript-eslint/eslint-plugin@2.x @typescript-eslint/parser@2.x babel-eslint@10.x eslint@6.x eslint-plugin-flowtype@4.x eslint-plugin-import@2.x eslint-plugin-jsx-a11y@6.x eslint-plugin-react@7.x eslint-plugin-react-hooks@2.x
```

Then create a file named `.eslintrc.json` with following contents in the root folder of your project:

```json
{
  "extends": "@zlph/eslint-config-react-app"
}
```
