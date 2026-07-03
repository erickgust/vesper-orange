# Vesper Orange

~~Peppermint and~~ orange flavored dark theme for [Zed](https://zed.dev), ported from [Vesper](https://github.com/raunofreiberg/vesper).

## About

This is Vesper ported to Zed, with [Igor Bedesqui's "no-peppermint" override](https://gist.github.com/bdsqqq/8f6e9d456bcd8b5f3f139c54a513af86) applied on top. That override is a VS Code settings snippet that swaps out Vesper's mint accents for grey, and this theme carries the same idea over to Zed, plus a couple of extra tweaks.

## What's different from stock Vesper

- Strings and symbols are grey instead of mint.
- In the git gutter: new files are still mint.

Zed themes can't target individual languages the way VS Code can, so a few of these colors end up applying more broadly than they did in the original.

## Install

```bash
cp vesper-orange.json ~/.config/zed/themes/vesper-orange.json
```

Then open the theme selector in Zed (`theme selector: toggle`) and pick **Vesper Orange**.

## Credits

- [Rauno Freiberg](https://github.com/raunofreiberg) made the original [Vesper](https://github.com/raunofreiberg/vesper) theme.
- [Igor Bedesqui](https://github.com/bdsqqq) did the first Zed port ([vesper-zed](https://github.com/bdsqqq/vesper-zed)) and wrote the [override](https://gist.github.com/bdsqqq/8f6e9d456bcd8b5f3f139c54a513af86) this theme is based on.

This is just a personal remix on top of their work.
