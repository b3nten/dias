<div align="center">
<br />

![Dias](.github/banner.jpg)

### Dias
#### Deno and Node minimal starter package

[![Npm package yearly downloads](https://badgen.net/npm/dy/express)](https://npmjs.com/package/express)
[![GitHub stars](https://img.shields.io/github/stars/freeCodeCamp/freeCodeCamp.svg?style=social&label=Star&maxAge=2592000)](https://github.com/freeCodeCamp/freeCodeCamp)
[![NuGet stable version](https://badgen.net/nuget/v/newtonsoft.json)](https://nuget.org/packages/newtonsoft.json)

*A minimal starter template for Deno libraries that can be converted and published to NPM. To use, clone and `rm -r .git`*
</div>

### Scripts

#### Dev
```sh
deno task dev
```
#### Test
```sh
deno task test
```
#### NPM
Ensure the NPM configuration is correct in `scripts/build.ts`.
```sh
deno task npm 0.0.1
```
#### Build
Build mod.ts as a minified js file.
```sh
deno task build
```