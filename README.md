# scala-steward-mine

[![CI](https://github.com/keyno63/scala-steward-mine/actions/workflows/ci.yaml/badge.svg)](https://github.com/keyno63/scala-steward-mine/actions/workflows/ci.yaml)
[![Scala Steward badge](https://img.shields.io/badge/Scala_Steward-helping-blue.svg?style=flat&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAQCAMAAAARSr4IAAAAVFBMVEUAAACHjojlOy5NWlrKzcYRKjGFjIbp293YycuLa3pYY2LSqql4f3pCUFTgSjNodYRmcXUsPD/NTTbjRS+2jomhgnzNc223cGvZS0HaSD0XLjbaSjElhIr+AAAAAXRSTlMAQObYZgAAAHlJREFUCNdNyosOwyAIhWHAQS1Vt7a77/3fcxxdmv0xwmckutAR1nkm4ggbyEcg/wWmlGLDAA3oL50xi6fk5ffZ3E2E3QfZDCcCN2YtbEWZt+Drc6u6rlqv7Uk0LdKqqr5rk2UCRXOk0vmQKGfc94nOJyQjouF9H/wCc9gECEYfONoAAAAASUVORK5CYII=)](https://scala-steward.org)

keyno63's personal scala-steward repository.

## Usage

- [scala-steward-org/scala-steward-action](https://github.com/scala-steward-org/scala-steward-action) テンプレートを使わせてもらっています  
- GitHub App を作成します（自分以外から commit してほしいため）
  - [GitHub App の作成](https://github.com/settings/apps) から App を作成します
  - private key の作成を忘れずに
- GitHub Token を作成します
- Secret に App private key を設定します
- GitHub Action から実行してもらいます
  - [GitHub App を使う場合](https://github.com/scala-steward-org/scala-steward-action#using-a-github-app-to-author-pull-requests) を参考にしてます
  - [GitHub Actions](./.github/workflows/ci.yaml) の設定を参照
- [repos.md](./repos.md) に監視対象のレポジトリーを記載します
- GitHub Actions を有効化します

以下のブログにもやり方などを記載
- [scala\-steward を個人レポジトリの GitHub Actions で動作させられた記録](https://keyno63.hatenablog.com/entry/2021/11/28/053042?_ga=2.82638870.1098984849.1637649578-931839124.1627922736)

## LICENSE

This repository is MIT License.  
see [License](./LICENSE) file.
