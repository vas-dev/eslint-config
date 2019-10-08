# @vas-dev/eslint-config

[`eslint`](https://eslint.org/) config for VAS projects based on [`react-app`](https://github.com/facebook/create-react-app/tree/master/packages/eslint-config-react-app) and [`standard`](https://github.com/standard/eslint-config-standard)

## Usage

If using `create-react-app`:

1. Add as `devDependency`
    ```sh
    yarn add --dev @vas-dev/eslint-config
    ```
2. Add to `package.json`
    ```json
    "eslintConfig": {
      "extends": "@vas-dev"
    },
    ```

If not using `create-react-app`:

1. Add dependencies
    ```sh
    yarn add --dev eslint babel-eslint eslint-config-react-app eslint-plugin-flowtype eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-react-hooks
    ```
2. Add to `package.json`
    ```json
    "eslintConfig": {
      "extends": "@vas-dev"
    },
    ```

## Rule Overrides

```
"no-console": "error",
"object-curly-spacing": ["error", "always"],
"react-hooks/rules-of-hooks": "error",
"prefer-promise-reject-errors": "off",
"jest/consistent-test-it": ["error", { "fn": "it" }],
"jest/no-empty-title": "error",
"jest/no-truthy-falsy": "error",
"jest/no-test-return-statement": "error",
"jest/no-test-callback": "error",
"jest/prefer-to-be-null": "error",
"jest/prefer-to-be-undefined": "error",
"jest/prefer-to-have-length": "error",
"jest/prefer-to-contain": "error",
"jest-formatting/padding-before-test-blocks": "error",
"jest-formatting/padding-before-describe-blocks": "error"
```
