# axomdbook

Customized [mdbook theme](https://rust-lang.github.io/mdBook/format/theme/index.html) for axo.dev projects (WIP)

Based on [oranda-css](https://github.com/axodotdev/oranda/tree/main/oranda-css).


# Usage

This adds two non-standard mdbook themes:

* axo (variant of mdbook's "navy")
* axo-light (variant of mdbook's "light")

In principle all you need to do to add this theme to your mdbook is:

* copy the `theme` dir into your mdbook
* edit your book.toml to include

```toml
[output.html]
default-theme = "axo"
preferred-dark-theme = "axo"
```
