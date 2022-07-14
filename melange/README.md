# melange-basic-template

A simple project template using [Melange](https://github.com/melange-re/melange).

## Quick Start

```shell
npm install
esy mel build
```

The ppx should replace `[%hello]` with string `Hello World!` in compiled Main.re file

Run compiled js file
```
node _build/default/src/Main.bs.js
```
Output:
```
Hello World!
```
