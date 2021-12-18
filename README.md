# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html).

## Install

```
$ pnpm add -D @pilchard/tsconfig
```

## Usage

`tsconfig.json`

```json
{
  "extends": "@pilchard/tsconfig/tsconfig.json",
  "compilerOptions": {
    "outDir": "dist"
  }
}
```

When targeting higher versions of Node.js, [check](https://node.green/#ES2022) the relevant ECMAScript version and add it as `target`:

```json
{
  "extends": "@pilchard/tsconfig/tsconfig.json",
  "compilerOptions": {
    "outDir": "dist",
    "target": "ES2022"
  }
}
```
