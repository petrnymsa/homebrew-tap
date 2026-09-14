# petrnymsa/homebrew-tap

Homebrew casks for [petrnymsa](https://github.com/petrnymsa)'s tools.

```sh
brew install --no-quarantine petrnymsa/tap/bequiet
```

| cask | what | source |
|---|---|---|
| `bequiet` | pauses Spotify, Apple Music and browser media while the microphone is in use | [be_quiet](https://github.com/petrnymsa/be_quiet) |

The apps are ad-hoc signed, so install with `--no-quarantine` (or set
`HOMEBREW_CASK_OPTS=--no-quarantine`); otherwise Gatekeeper refuses to open
them.
