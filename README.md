Reproducing of https://github.com/jrburke/r.js/issues/803

`main-built.js` is the file generated via `build.cmd`.

Please review `main-built.js`.
You will see several `define`s without an `ID`.
Corresponding source files contain `define` without `factory` function.

Please open `index.html` and check console.
You will see several log messages.

Please open `index-built.html` and check console.
You will see `"Mismatched anonymous define() module: undefined"` message.
