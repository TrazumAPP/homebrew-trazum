# homebrew-trazum

The Homebrew tap for [Trazum](https://github.com/Davmunrey/Trazum), which
prices AI agent usage from the logs on your machine, offline.

```
brew tap Davmunrey/trazum
brew install trazum
trazum --version
```

The formula installs `@trazum/cli` from npm and needs Node, which Homebrew
installs with it.

## Where the formula comes from

`Formula/trazum.rb` is not edited here. It is written in the main repository
by `scripts/homebrew-formula.mjs`, from the tarball npm serves, with that
tarball's SHA-256. After each release the maintainer copies the new file in by
hand, so this tap can name an older version than npm for a while. `npm install
-g @trazum/cli` always has the newest.

Issues and changes belong in [Davmunrey/Trazum](https://github.com/Davmunrey/Trazum).
