# Rust hooks for pre-commit

[Rust](https://www.rust-lang.org) tools package for [pre-commit](https://pre-commit.com).

Forked from: [doublify's pre-commit-rust](https://github.com/doublify/pre-commit-rust) (**NOTE: Their repo is unmaintained**)

## Using rust tools with pre-commit

```yaml
-   repo: https://github.com/antonio-hickey/rusted-pre-commits
    rev: master
    hooks:
    -   id: fmt
    -   id: cargo-check
    -   id: clippy
    -   id: build
    -   id: test
```

## Passing arguments to rustfmt

```yaml
-   repo: https://github.com/antonio-hickey/rusted-pre-commits
    rev: master
    hooks:
    -   id: fmt
        args: ['--verbose', '--edition', '2021', '--']
```
