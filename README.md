# scala-steward-mine

自分用に scala-steward を実行するレポジトリー

## Usage

- [scala-steward-org/scala-steward-action](https://github.com/coursier/cache-action) テンプレートを使わせてもらっています  
- GitHub Action から実行してもらいます
  - [GitHub Actions](./.github/workflows/ci.yaml) の設定を参照
- [repo.md](./repo.md) に監視対象のレポジトリーを記載します
- token を Secret に設定してください
  - GitHub の Developer Settings で作成する token のことです
- GitHub Actions を有効化します

## LICENSE

This repository is MIT License.  
see [License](./LICENSE) file.
