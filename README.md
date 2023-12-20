# practice-ruby
ruby練習用

## Dockerで環境構築
- イメージ作成
```bash
docker build ./docker -t ruby_image
```
- コンテナ作成
```bash
docker run -it -d --name ruby_container ruby_image
```
- コンテナへ入る
```bash
docker exec -it ruby_container bash
```

## ワンライナー
```ruby
ruby -e 'puts "hoge"'
```

# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
