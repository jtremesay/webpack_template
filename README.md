My template app for a typescript + webpack project.

From scratch commands:

```
direnv allow # only if you use nix-shell + direnv
npm install --save-dev
npm run serve
```

Available commands:
- `npm run build`: build the project
- `npm run watch`: continuous build of the project
- `npm run serve`: start a development server


Relevant documentations:
- [Webpack guides](https://webpack.js.org/guides/):
  - [Getting started](https://webpack.js.org/guides/getting-started/)
  - [Asset management](https://webpack.js.org/guides/asset-management/)
  - [Output management](https://webpack.js.org/guides/output-management/)
  - [Typescript](https://webpack.js.org/guides/typescript/)
  - [Development](https://webpack.js.org/guides/development/)
  - [Code spliting](https://webpack.js.org/guides/code-splitting/)
  - [Caching](https://webpack.js.org/guides/caching/)
  - [Hot module replacement](https://webpack.js.org/guides/hot-module-replacement/)
  - [ECMA script module](https://webpack.js.org/guides/ecma-script-modules/)
- Nix stuff:
  - [nix-shell](https://nixos.org/manual/nix/unstable/command-ref/nix-shell.html) 
  - [direnv](https://direnv.net/)
