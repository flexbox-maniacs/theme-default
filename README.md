# theme-default setup

## dependencies:

- sass
- [dependecies project](https://github.com/flexbox-maniacs/dependencies)

## aliases:
### `tsconfig.json`: compilerOptions.paths

- `"@theme": ["./node_modules/{YOUR THEME DEFAULT FOLDER}/scss/main.scss"]`
- `"@functions": ["./node_modules/@flex/dependencies/sass/functions"]`


### `vite.config.ts`: defineConfig.resolve.alias
(`import * as path from "path"`)

- `"@theme": path.resolve(__dirname, "./node_modules/{YOUR THEME DEFAULT FOLDER}/scss/main.scss")`
- `"@functions": path.resolve(__dirname, "./node_modules/@flex/dependencies/sass/functions")`

## general configuration

- `import "@theme"` in main file
