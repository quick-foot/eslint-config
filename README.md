# eslint-config

Quick and easy eslint config for Angular projects

## Installation

`npm i -D eslint @quick-foot/eslint-config`

## Usage

`.eslintrc.json`

```json
{
    "extends": "@quick-foot/eslint-config"
}
```

## Requirements

-   eslint @ >= 5.0.0
-   typescript @ >=3.2.1 <3.4.0

## Help

#### VS Code not showing eslint output for TypeScript files

To enable eslint parsing of TypeScript files, add this to your VS Code Settings, specifically the typescript language
object.

```json
{
    "eslint.validate": ["javascript", { "language": "typescript", "autoFix": true }]
}
```

This will not be needed once https://github.com/Microsoft/vscode-eslint/issues/609 is resolved.
