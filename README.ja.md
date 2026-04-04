# cmux Intel Mac Builds

> [English](README.md)

[cmux](https://github.com/manaflow-ai/cmux) の Intel Mac (x86_64) 自動ビルド。

上流リリースを6時間ごとにチェックし、新バージョン検出時に署名なし x86_64 ビルドを作成・公開する。

## Homebrew でインストール

```sh
brew install webkaz/tap/cmux-intel
```

更新:

```sh
brew upgrade --cask cmux-intel
```

## 手動ダウンロード

[Releases](https://github.com/webkaz/cmux-intel-builds/releases) から DMG を取得。

署名なしビルドのため、初回起動時:

```sh
xattr -cr /Applications/cmux.app
```

または右クリック → "開く" を選択。
