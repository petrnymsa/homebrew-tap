# petrnymsa/homebrew-tap

Homebrew casks for [petrnymsa](https://github.com/petrnymsa)'s tools.

```sh
brew trust petrnymsa/tap
brew install --cask petrnymsa/tap/bequiet
```

| cask | what | source |
|---|---|---|
| `bequiet` | pauses Spotify, Apple Music and browser media while the microphone is in use | [be_quiet](https://github.com/petrnymsa/be_quiet) |

`brew trust` is needed since Homebrew 6. The apps are ad-hoc signed, so
Gatekeeper refuses the first launch: allow it under System Settings → Privacy &
Security → *Open Anyway*, or run `xattr -dr com.apple.quarantine` on the app.
