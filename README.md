# text-lint-vscode

## 概要
vscodeに文章を貼りつけるだけで日本語の校生を行えるようにする環境を構築する。

## 導入方法

1. vscodeのインストール
1. 以下のブランチをcloneする
    ```
    git@github.com:hashiserver/text-lint-vscode.git
    ```
1. text-lint-vscodeディレクトリにて以下のコマンドを実行
    ```
    yarn install
    ```
1. vscodeのプラグインを追加
    ```
    vscode-text
    ````
1. .txtファイルや.mdファイルを作成し記述する
1. 保存した時点でテキスト校生がされて、誤っている文章はエラーとして表示される

## 本リポジトリに有効化しているルール

- https://github.com/textlint-ja/textlint-rule-preset-ja-spacing
- https://github.com/textlint-ja/textlint-rule-preset-ja-technical-writing
- https://github.com/azu/textlint-rule-spellcheck-tech-word

