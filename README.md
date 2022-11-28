# GitHubActionTests

リポジトリは GitHub Actions のサポート状況をチェックするために使用します. 以下のパラメータに従ってブランチを分け, いつでも実行できるように準備します.

- macOS version
- Swift version

公式 : https://github.com/actions/runner-images

## 使い方

- 各ブランチは Swift バージョンに対応しています.
- 一つのブランチに複数の macOS バージョンのテストを含んでいます.
- 新しい Swift バージョンブランチを作成する場合は feat/base からブランチを作成して編集します.
- PR は develop ブランチに対して行います.

## 注意

- このリポジトリは公式の GitHub Actions の品質を保証するためのものではありません.
- Actions が使えるかチェックするには, その時に Action を実行してチェックする必要があります. つまりこのリポジトリは完全に私用ということになります. なんなら macOS しかチェックしてません.
- Action の公式のサポート情報や Apple の Xcode とそれに対応する Swift バージョンを確認すればわかるようなことしかしません.
