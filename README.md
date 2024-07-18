[[_TOC_]]

# Svenska Akademins Ordlista (SAOL)

Svenska Akademins Ordlista för MacOS, Linux och Windows.

## Installera

# Contribute

## Setup the development environment

```
yarn install
```

This project uses the Yarn pnp instead of the old node_modules. At the time of writing, VSCode (with the ESLint extension) does not find the installed dependencies when writing typescript files, i.e., `import something from package` throws linting errors. Follow [Yarn's instructions](https://yarnpkg.com/getting-started/editor-sdks) on setting up VSCode.
