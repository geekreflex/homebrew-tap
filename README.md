# homebrew-tap

Homebrew tap for [@geekreflex](https://github.com/geekreflex)'s tools.

## Install

```bash
brew install geekreflex/tap/envcheck
```

Or tap it once and install by name:

```bash
brew tap geekreflex/tap
brew install envcheck
```

## Available formulae

| Tool | Description |
| --- | --- |
| [envcheck](https://github.com/geekreflex/envcheck) | Catch missing environment variables before they break production |

## How this repository is maintained

**Do not edit `Casks/` by hand.** The cask definitions here are generated and
committed automatically by [GoReleaser](https://goreleaser.com) when a release
is tagged in the source repository. Any manual change will be overwritten by
the next release.

To fix a packaging problem, change the `homebrew_casks` block in the source
repository's `.goreleaser.yaml` and cut a new release.

Casks are macOS-only. On Linux, install from the release archives or with
`go install`.
