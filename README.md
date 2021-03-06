# Emacs config

## Requirements

### C/C++/ObjC
The [query][query] LSP server is used to provide IDE features, like
auto-completion, diagnostics, code naviation, code actions, and
such.

### Go
`go-mode.el` relies heavily on tooling:

+ `godoc`
+ `gofmt`
+ `godef`
+ `goreturns`
+ `gorename`
+ `guru`

### Markdown
Markdown command is set to `markdown`. On Fedora this is provided by the
`discount` package.

### Python
Python also uses the [python language server][pyls]. Install with:
`pip install --user 'python-language-server[all]'`

On Fedora, some system packages can be used:
+ `python3-future`
+ `python3-jsonrpclib`
+ `python3-pycodestyle`
+ `python3-pyflakes`
+ `pythno3-rope`

### Writing
Synosaurus uses wordnet (`brew install wordnet`) and langtool needs the jar (`brew install langtool`).

[query]: https://github.com/cquery-project/cquery
[pyls]: https://github.com/palantir/python-language-server
