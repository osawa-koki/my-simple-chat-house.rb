# my-simple-chat-house.rb

🥦🥦🥦 `Ruby on Rails` × `Next.js`で作成した簡単なルーム機能付きチャットアプリです。  
ルーム機能を実装しているので、複数のユーザーが同じルームでチャットができます。  

![成果物](./docs/img/fruit.gif)  

## 実行方法

```shell
docker build -t my-simple-chat-house-rb .
docker run -it -p 8000:8000 --name my-simple-chat-house-rb my-simple-chat-house-rb
```

## 使用している技術

- Next.js
  - React
  - TypeScript
  - Bootstrap
- Ruby
  - Ruby on Rails
  - API mode
  - Action Cable (WebSocket)
- Docker
- GitHub
  - Repository
  - GitHub Actions

## 自分用メモ

転職先の企業でRuby(Rails)を使うことになったので、学習用に、、、  

```shell
gem install rails
rails new . --database=sqlite3 --api
```

### コントローラの作成

```shell
rails g controller コントローラ名 アクション名
```

### モデルの作成

```shell
rails g model モデル名 カラム名:データ型
rails db:migrate
```
