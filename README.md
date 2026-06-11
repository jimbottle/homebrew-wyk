# homebrew-wyk

Homebrew tap for [wyk (would-you-kindly)](https://github.com/jimbottle/would-you-kindly) —
a terminal UI over the [beads](https://github.com/gastownhall/beads) issue tracker,
built for the moment an agent hands work back to a human.

```bash
brew install jimbottle/wyk/wyk
```

The cask in `Casks/` is generated and pushed by
[goreleaser](https://goreleaser.com) on each tagged release of wyk —
do not edit it by hand. wyk shells out to the `bd` (beads) binary;
install it separately: https://github.com/gastownhall/beads
