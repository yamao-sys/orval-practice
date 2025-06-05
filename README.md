# orval-practice
Orvalの検証

REST APIのアプリケーションでReactでOpenAPIからのAPIクライアントと型生成でopenapi-typescript, openapi-fetchを使用していたが、手動で作成する範囲が広くて悩ましいと思っていたため、別の自動生成ライブラリを検証してみたい。

Tanstack Queryとの相性の良さを活かせるらしいのでOrvalを検証

## 所管
以下の点が嬉しい
- tagsごとにディレクトリ分けてくれる
- models(components/schemas)を別ディレクトリに切ってくれる
- コード自動生成後のhookを設定できて、そのままprettierをかけられる
- 自動生成されてほしい内容はOpenAPI Generatorと遜色なしだし、Tanstack Query向けに作ってくれるのでセットで使えば威力を発揮しそう

## 参考
- https://fintan.jp/page/4857/
- https://zenn.dev/hrbrain/articles/3ca5d37dd0b80e
- https://orval.dev/quick-start
- https://orval.dev/guides/react-query
- https://orval.dev/reference/configuration/overview
