# simtabi/homebrew-tap

Homebrew tap for [simtabi](https://github.com/simtabi) developer tools.

## Usage

```bash
brew tap simtabi/tap
brew install simtabi/tap/shimkit
```

## Casks

- **authama** — Authentication Access Manager: SSH keys and config, and auth
  tokens for Composer, npm, Docker, git and netrc.
  `brew install --cask simtabi/tap/authama`
  ([upstream](https://github.com/simtabi/authama)). Formerly the `sshmgr`
  cask: `cask_renames.json` maps `sshmgr` to `authama`, so an existing install
  moves over on `brew update && brew upgrade`. The cask is published by
  authama's release workflow; do not hand-edit `Casks/authama.rb`.

## Formulae

- **shimkit** — A toolkit of developer utilities. Python tools, shimmed
  by bash. ([upstream](https://github.com/simtabi/shimkit))

## How formulas land here

Formulas are bumped automatically by the
[`release.yml`](https://github.com/simtabi/shimkit/blob/main/.github/workflows/release.yml)
workflow in the upstream repo on every tag push. Do not hand-edit
`Formula/*.rb` — the next release will overwrite your changes.
