# theme-default setup

## dependencies:

- sass
- [dependecies project](https://github.com/flexbox-maniacs/dependencies)

## aliases:
### `tsconfig.json`: compilerOptions.paths

- `"@theme": ["./node_modules/{YOUR THEME DEFAULT FOLDER}/scss/main.scss"]`

### `vite.config.ts`: defineConfig.resolve.alias
(`import * as path from "path"`)

- `"@theme": path.resolve(__dirname, "./node_modules/{YOUR THEME DEFAULT FOLDER}/scss/main.scss")`

## general configuration

- `import "@theme"` in main file
