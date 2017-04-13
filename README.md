# Rust hooks for pre-commit

[Rust](https://www.rust-lang.org) tools package for [pre-commit](http://pre-commit.com).

## Using rust tools with pre-commit

```yaml
-   repo: git://github.com/doublify/pre-commit-rust
    sha: master
    hooks:
    -   id: fmt
```
