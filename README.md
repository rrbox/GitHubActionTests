# GitHubActionTests

GitHub Action の管理をするときに, パッケージごとにバージョン管理をするのが大変でした. このリポジトリでは Action のサポート状況をチェックするために使用します. 以下のパラメータに従ってブランチを分け, いつでも実行できるように準備します.

- macOS version
- Swift version

公式 : https://github.com/actions/runner-images

## 使い方

- 各ブランチは Swift バージョンに対応しています.
- 一つのブランチに複数の macOS バージョンのテストを含んでいます.
- 新しい Swift バージョンブランチを作成する場合は feat/base からブランチを作成して編集します.
- PR は develop ブランチに対して行います.
