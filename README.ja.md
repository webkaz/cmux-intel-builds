# cmux Intel Mac Builds（配布終了）

> [English](README.md)

このリポジトリでは、以前
[cmux](https://github.com/manaflow-ai/cmux) の Intel Mac（x86_64）向け
非署名ビルドを配布していました。

上流プロジェクトが Intel Mac と Apple Silicon Mac の両方に対応する、署名・notarize済みの
公式Universal Buildを配布するようになったため、このリポジトリでの新規ビルド配布を終了します。

## 公式Homebrew caskへの移行

cmuxを終了してから、次を実行してください。

```sh
brew uninstall --cask cmux-intel
brew tap manaflow-ai/cmux
brew install --cask cmux
```

既存の設定やアプリケーションデータを残す場合、アンインストール時に `--zap` を付けないでください。

今後の更新は次のコマンドで行えます。

```sh
brew upgrade --cask cmux
```

## 公式DMGからのインストール

署名済みUniversal DMGは
[cmux公式Releases](https://github.com/manaflow-ai/cmux/releases/latest) から取得できます。

## 過去のビルド

[このリポジトリのReleases](https://github.com/webkaz/cmux-intel-builds/releases) は履歴として残します。
これらは非署名・サポート対象外で、セキュリティ更新や互換性更新は提供されません。
