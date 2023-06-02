# REST について理解する

## REST API について自分の言葉でまとめてください

API は`Application Programming Interface`の頭文字を取ったものです。
機能やデータを外部から呼び出して利用できるように定めた規約です。

REST とは`REpresentational State Transfer`の略で

日本語に直すと、分散型システムにおける設計原則群という意味があります。

さらにわかりやすく説明すると設計ルールという意味です！

基本的にルールこのようになります
REST ６原則

- クライアント/サーバー
- ステートレス
- キャッシュ制御
- 統一インターフェース
- 階層化システム
- コードオンデマンド

これらを守った API が REST API となります。

REST API とは、この REST 原則に基づいて設計された API のことを指します！

システム開発で出てくる`REST`は休憩することではありません！！

## movie をリソースとして CRUD 操作の URI、HTTP メソッドを定義してください

| URI                                  | HTTP method | 操作                     |
| ------------------------------------ | ----------- | ------------------------ |
| https://api.example.com/movies       | GET         | ムービー情報一覧画面取得 |
| https://api.example.com/movies       | POST        | ムービーの新規登録       |
| https://api.example.com/movies/12345 | PUT         | ムービーの更新、登録     |
| https://api.example.com/movies/12345 | DELETE      | ムービーの削除           |
