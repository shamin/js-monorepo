# js-monorepo

## Running the project
Bootstrap the project (This will install & setup dependencies)
```
npm run bootstrap
```

Start `app` project and watch package builds
```
npm start
```


### Creating new package
```sh
npm run create-package <package-name> [<location>] -- [options]
```

### Installing deps to app/package
```
npm run install <dep-package-name> [--scope=<app/package>]
```
Eg:
```
npm run install @js-monorepo/tsconfig -- --scope @js-monorepo/app --dev
```