# README

## 環境構築
```
$ bundle install --without=production
$ bin/rails db:setup
$ yarn install
$ bin/webpack
$ bin/rails s
```

## 事業をエンジニアリングしよう提案編の回答は以下に記述してください
### 選択した事業側の課題
サービス登録者数の内、男性60%に対して、女性は40%。一方で、サービス内のもくもく会に参加した人の比率は、男性90%：女性10%と大きな差が出ています。もっと女性が使いやすいようなサービス設計にする必要があるのではないか？

### 提案内容
- 参加するメンバーの男女比を表示する機能を実装する。男女比が大きく偏っているもくもく会を避けることができ、女性ユーザーが参加しやすくなると考えられる。
- 女性専用のもくもく会を開催する機能を実装する。

### 実装方針
- ユーザー登録の際、性別を選択。プロフィールに表示。
- 女性専用のもくもく会は、女性以外は表示されなくする。
- 一覧画面に男女比を表示する。
