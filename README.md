# simtabi/homebrew-tap

Homebrew tap for [simtabi](https://github.com/simtabi) developer tools.

## Usage

```bash
brew tap simtabi/tap
brew install simtabi/tap/shimkit
```

## Casks

- **osaat** — audit and back up installed applications on macOS, Linux and
  Unix. `brew install --cask simtabi/tap/osaat`
  ([upstream](https://github.com/simtabi/osaat)).

authama is not published here while its binary releases are on hold: build it
from source ([installation](https://github.com/simtabi/authama/blob/main/docs/installation.md)).
Its cask, and the `sshmgr` → `authama` rename that pointed at it, were removed
because they named v0.1.3 downloads that no longer exist. The next authama
release publishes the cask again.

## Formulae

- **shimkit** — A toolkit of developer utilities. Python tools, shimmed
  by bash. ([upstream](https://github.com/simtabi/shimkit))

## How formulas land here

Formulas are bumped automatically by the
[`release.yml`](https://github.com/simtabi/shimkit/blob/main/.github/workflows/release.yml)
workflow in the upstream repo on every tag push. Do not hand-edit
`Formula/*.rb` — the next release will overwrite your changes.
