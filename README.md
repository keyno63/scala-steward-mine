# scala-steward-mine

自分用に scala-steward を実行するレポジトリー

## Usage

- [scala-steward-org/scala-steward-action](https://github.com/coursier/cache-action) テンプレートを使わせてもらっています  
- GitHub App を作成します（自分以外から commit してほしいため）
  - [GitHub App の作成](https://github.com/settings/apps) から App を作成します
  - private key の作成を忘れずに
- GitHub Token を作成します
- Secret に App private key と Token を設定します
- GitHub Action から実行してもらいます
  - Github Action の設定を作成します
  - [GitHub App を使う場合](https://github.com/scala-steward-org/scala-steward-action#using-a-github-app-to-author-pull-requests) を参考にしてます
  - [GitHub Actions](./.github/workflows/ci.yaml) の設定を参照
- [repos.md](./repos.md) に監視対象のレポジトリーを記載します
- GitHub Actions を有効化します

## LICENSE

This repository is MIT License.  
see [License](./LICENSE) file.
