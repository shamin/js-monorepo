# js-monorepo

## Running the project

## Creating new package
```sh
npm run create-package <package-name> [<location>] -- [options]
```

## Installing deps to app/package
```
npm run add <dep-package-name> [--scope=<app/package>]
```
Eg:
```
npm run install @js-monorepo/tsconfig -- --scope @js-monorepo/app --dev
```