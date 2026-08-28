# Homebrew tap for Perch

Run Claude Code as whichever Claude account you want, without logging in again.

```sh
brew tap perch-cli/perch
brew install perch
```

Perch itself, and anything you might actually want to read, lives at
[perch-cli/perch](https://github.com/perch-cli/perch). Issues belong there
too.

## About this repository

It holds one file, `Formula/perch.rb`, and that file is generated. Every Perch
release regenerates it and pushes it here, with the download URLs and the
SHA-256 of each archive taken from the checksums that release published — so
the formula can only ever point at bytes that are on Perch's releases page.

Nothing here is edited by hand, and an edit would be overwritten by the next
release. It exists as a repository of its own only because Homebrew requires
one: `brew tap perch-cli/perch` looks for `perch-cli/homebrew-perch`, and the
prefix is not optional.

Perch is pre-1.0. A tap is a deliberate thing to add, which is exactly why it
is the right place for it until then.
