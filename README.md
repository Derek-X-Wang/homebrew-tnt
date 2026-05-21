# homebrew-tnt

Homebrew tap for [Derek-X-Wang/tnt](https://github.com/Derek-X-Wang/tnt) — voice-first **Personal Master Agent** for macOS.

## Install

```sh
brew tap Derek-X-Wang/tnt
brew install --cask tnt
```

After install, launch TNT from Applications. Auto-updates are handled in-app by Sparkle; `brew upgrade --cask tnt` is fine too but optional.

## What's here

| Path | Purpose |
| --- | --- |
| `Casks/tnt.rb` | The macOS `.dmg` install (the actual product) |
| `Formula/tnt.rb` | Placeholder formula until TNT ships a standalone CLI tarball — install via the cask instead |

Both files are **auto-generated** by [`scripts/render-homebrew.py`](https://github.com/Derek-X-Wang/tnt/blob/main/scripts/render-homebrew.py) in the upstream repo on each release. Direct edits here will be overwritten.

## License

[Apache-2.0](./LICENSE). Same license as the upstream TNT repo.
