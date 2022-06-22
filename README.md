## 概要
LaravelのDocke開発環境サンプル

## 開発環境構築手順

```
$ git clone git@github.com:shintarou-akao/docker-laravel-sample.git
$ cp .env.example .env
$ docker compose up -d --build
$ docker compose exec app bash
# composer create-project --prefer-dist laravel/laravel .
```
## 参考
- [DockerでPHP（Laravel）+ nginx + MySQLのLEMP環境を構築する](https://qiita.com/hinako_n/items/f15646ea548bcdc8ac6c)
