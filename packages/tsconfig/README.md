# `@js-monorepo/tsconfig`

> Reusable typescript configuration

## Usage

Add this to your `tsconfig.json`
```js
{
  "extends": "@js-monorepo/tsconfig",
  "include": ["src"],
  "exclude": ["node_modules", "**/__tests__/*"],
  "compilerOptions": {
    "outDir": "dist"
  }
}
```
