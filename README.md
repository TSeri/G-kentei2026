# G検定 読む・解く・復習（Webアプリ）

`index.html` 1ファイルで動きます。外部ライブラリなし。学習記録は端末の localStorage に保存。

公開URL: https://tseri.github.io/G-kentei2026/

iPhone の Safari で開き、共有 →「ホーム画面に追加」するとアプリのように使えます。

## 章を増やす
`index.html` 内の `CHAPTERS` 配列に同じ形式で追加。本文中の `【用語】` は `TERMS` に定義があればタップで開く。
復習カードは `CARDS` に `[表, 裏, "year"|"person"|"term"]` を追加。

## 関連
学習管理用の R スクリプト群と問題集は非公開リポジトリ TSeri/GK2026 で管理しています。
