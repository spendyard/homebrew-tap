# Spendyard's Homebrew tap

```bash
brew install spendyard/tap/spendyard
```

installs [`spendyard`](https://github.com/spendyard/spendyard), which reads receipts and invoices and works out what you're paying for, for macOS and Linux, as a cask: it's already built, so Homebrew doesn't need Xcode's Command Line Tools for it.

To update it: `brew upgrade spendyard/tap/spendyard`. Homebrew 6 and later leaves third-party taps out of a plain `brew upgrade`, and out of commands that don't name them in full, until you trust them; to have `brew upgrade` include spendyard:

```bash
brew trust spendyard/tap
```

`Casks/spendyard.rb` is written by the [spendyard repository's release workflow](https://github.com/spendyard/spendyard/blob/main/.github/workflows/release.yml) for each release, from the release's checksums: don't edit it by hand.

Other ways to install, and what `spendyard` does: [github.com/spendyard/spendyard](https://github.com/spendyard/spendyard).

## License

[Apache License 2.0](LICENSE).
