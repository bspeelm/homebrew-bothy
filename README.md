# homebrew-bothy

A Homebrew tap for [bothy](https://github.com/bspeelm/bothy) — a turn-key
terminal workspace built from tools you already trust.

```sh
brew install bspeelm/bothy/bothy
```

## This repository is generated

`Casks/bothy.rb` is written by GoReleaser from a tag in the bothy repository,
so its version is derived from the release rather than bumped by hand. Do not
edit it: the next release overwrites it.

Issues and pull requests belong on
[bspeelm/bothy](https://github.com/bspeelm/bothy/issues), not here.

## What `brew install` gets you

The binary, and nothing else. bothy fetches the tools it needs into its own
directory at first run rather than installing them system-wide, so this tap
declares no dependencies — installing zellij or yazi through Homebrew is the
opposite of what bothy does.
