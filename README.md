# tree-sitter-glua

[![build status](https://github.com/Azganoth/tree-sitter-lua/actions/workflows/ci.yml/badge.svg)](https://github.com/Azganoth/tree-sitter-lua/actions/workflows/ci.yml)

GLua grammar for tree-sitter.
Experimental, also comments are not handled because I almost had an aneurysm while attempting to make a grammar rule for comments.
Just use.. a preprocessor to change "//" to "--" and etc

For Rust usage see the [crate README][rust readme].

## References

- [Tree-sitter docs][tree-sitter docs]
- [Lua docs][lua docs]

## License

This package is licensed under the [MIT License][license].

[rust readme]: /bindings/rust/README.md
[tree-sitter docs]: http://tree-sitter.github.io/tree-sitter/
[lua docs]: https://www.lua.org/docs.html
[license]: /LICENSE.txt
