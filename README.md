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
