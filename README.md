## Project Setup

```sh
- npm install
- npm run dev
- npm run build
- npm run test:unit
- npm run test:e2e:dev
- npm run test:e2e
- npm run lint
```


## BLOB debug tool for VUE VITE 
 

## References
- https://developer.mozilla.org/en-US/docs/Web/API/Blob


## notes

- need a debug tool for VUE                      name: ViteBlob (eg:Redux DevTools,firebug)
- should export every JSON file and print able   print: HP printer 
- need a debug Extension for VSCode                   name: ViteBlob (eg:Redux DevTools,firebug)

## Certificate & Signature 
 **Halo Infinite - Microsoft**

# viteBlob

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
    1) Run `Extensions: Show Built-in Extensions` from VSCode's command palette
    2) Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).



### Compile and Hot-Reload for Development


### Type-Check, Compile and Minify for Production

### Run Unit Tests with [Vitest](https://vitest.dev/)


### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments):

```sh
npm run build
npm run test:e2e
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
