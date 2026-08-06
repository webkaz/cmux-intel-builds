# cmux Intel Mac Builds (Discontinued)

> [日本語版はこちら / Japanese](README.ja.md)

This repository previously published unsigned Intel Mac (x86_64) builds of
[cmux](https://github.com/manaflow-ai/cmux).

The upstream project now publishes an official signed and notarized universal
build that supports both Intel and Apple Silicon Macs. This repository no
longer publishes new builds.

## Migrate to the official Homebrew cask

Quit cmux, then run:

```sh
brew uninstall --cask cmux-intel
brew tap manaflow-ai/cmux
brew install --cask cmux
```

Do not add `--zap` when uninstalling if you want to preserve your existing
settings and application data.

Future updates are installed with:

```sh
brew upgrade --cask cmux
```

## Install from the official DMG

Download the signed universal DMG from the
[official cmux releases](https://github.com/manaflow-ai/cmux/releases/latest).

## Historical builds

The [releases in this repository](https://github.com/webkaz/cmux-intel-builds/releases)
are retained for historical reference. They are unsigned, unsupported, and do
not receive security or compatibility updates.
