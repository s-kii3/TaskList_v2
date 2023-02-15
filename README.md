# TaskList_v2
タスク管理アプリケーション v2
dockerを使って環境構築するよう変更

## 起動方法
```
# app配下に移動して、アプリケーションのビルド
cd ./app && gradle clean build

# docker-compose.ymlに移動して起動
cd .. && docker compose up -d
```

## URL
http://localhost:8080/

## 参考
https://qiita.com/monkey0001/items/2e14428831e9ad7f48b4
