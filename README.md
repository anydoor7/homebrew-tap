# homebrew-tap

Homebrew tap for [TSLink](https://github.com/anydoor7/tslink): private addresses for your apps, on your Tailscale network.

## Install

On macOS or Linux:

```bash
brew install --cask anydoor7/tap/tslink
```

Upgrade with `brew upgrade --cask tslink`, then run `tslink install` again if TSLink runs as a background service. On macOS the binary is Developer ID signed and notarized by Apple, so Gatekeeper runs it without any extra step.

Windows, `.deb` and `.rpm` downloads, and building from source are covered in [Getting started](https://github.com/anydoor7/tslink/blob/main/docs/getting-started.md). To check a download, see [verify a release](https://github.com/anydoor7/tslink/blob/main/docs/verify-release.md).

## How this tap is maintained

`Casks/tslink.rb` is generated and pushed by the TSLink release workflow (GoReleaser `homebrew_casks`) on every stable tag. Do not edit it by hand; changes belong in the [tslink](https://github.com/anydoor7/tslink) repository's `.goreleaser.yml`.

## License

The cask definition in this repository is released under the [Apache License 2.0](./LICENSE). TSLink itself is licensed separately in its own repository.
