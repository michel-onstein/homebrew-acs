# homebrew-acs

The [Homebrew](https://brew.sh) tap for
[acs](https://github.com/michel-onstein/acs) — *Ad-hoc Connectivity Shell*:
persistent, reconnecting remote shells over ssh with an unfiltered terminal
stream.

```sh
brew install michel-onstein/acs/acs
brew upgrade acs        # a brewed acs upgrades with brew, not acs upgrade
```

It installs the release build for your machine (macOS Apple silicon and
Intel, Linux x86_64 and aarch64), the same archive as the one-line
installer, so it can install acs on any Linux host it connects to.

`Formula/acs.rb` is generated: every acs release renders it
(`cargo xtask formula`) and commits it here (`scripts/update-tap.sh` in the
acs repository). Change the generator there rather than editing it here.
