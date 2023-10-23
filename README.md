<div align="center" style="background:linear-gradient(90deg, rgba(255,0,0,1) 0%, rgba(9,118,121,1) 100%); background-clip:text; color:transparent;">
<br />

![Dias](.github/banner.jpg)

### Dias
#### Deno and Node minimal starter package

<!-- ![GitHub Workflow Status](https://github.com/exhibitionist-digital/ultra/actions/workflows/ci.yml/badge.svg) -->
<!-- [![Deno module](https://shield.deno.dev/x/ultra)](https://deno.land/x/ultra) -->
![Deno compatibility](https://shield.deno.dev/deno/^1.3.7)

</div>

*A minimal starter template for Deno libraries that can be converted and published to NPM. To use, clone and `rm -r .git`*

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