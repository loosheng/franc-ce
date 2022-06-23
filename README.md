# franc-ce

[![NPM version](https://img.shields.io/npm/v/franc-ce?color=a1b858&label=)](https://www.npmjs.com/package/franc-ce)

The esm and commonJs compatible version of the franc library.

## Why does it exist ?

franc@6.0.0 is ESM Only,I can't use it in the vscode extension.

## User's Guide
```bash
pnpm i franc-ce 
# or yarn add franc-ce
# or npm add franc-ce
```
```diff
--- import {franc, francAll} from 'franc'
+++ import {franc, francAll} from 'franc-ce'
```


## License

[MIT](./LICENSE) License © 2022 [LooSheng](https://github.com/loosheng)
