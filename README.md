# template
テンプレート用です。
現在開発中のためうまく動作しない場合があります。

このGitHub Actionsは以下の設定してから使用する。
`Actions permissions`
`Read and write permissions`

以下のコマンドでissue labelをコピーできます。
```sh
gh label clone ENDOTAKUMI/template -R ユーザー名/コピー先のリポジトリ
```

以下の記事を参考にしてください  
https://zenn.dev/endotakumi/articles/fe05f350f6f506

## mainブランチへのプルリクエストに含める単語  
以下のタグをタイトルに含めることにより、各バージョンを上げることが出来ます。  
| バージョン名         | 説明                                                 | タグ       | 変更内容 |
|----------------------|------------------------------------------------------|------------|----------|
| メジャーバージョン   | 大部分のデザインや機能が変更されたとき               | [major]    | 大       |
| マイナーバージョン   | 一部機能の改善や、細かい追加機能が実装されたとき     | [minor]    | 中       |
| パッチバージョン     | 軽微なバグの修正や誤字や注釈表現を変更したとき      | [patch] / 上記に該当しない場合| 小       |
