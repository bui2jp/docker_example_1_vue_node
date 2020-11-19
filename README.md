# Docker SPA(Vue) WEBAPI(node)

docker,docker-composeを使って簡単なWEB環境を作成

```
% docker -v 
Docker version 19.03.5, build 633a0ea
```

## 構成 frontend + backend
```
frontend: vue-sb-admin2 SPA web画面
backend: api-server　RESTAPI Server
```

## Run & Stop

起動
```
% docker-compose up
```

確認 (Chromeでアクセス)
```
http://localhost:8080
```

削除
```
% docker-compose down
```
