# WITS DEV ENV

這是一個透過docker-compose 組織的 開發環境

docker-compose.yml 會啟用 
- mysql
- postgres
- redis
- adminer   # 一個簡易的 sql browser
  

啟用方式如下

```
docker-compose up -d
```

如果有對 yml做異動，也只需要下指令
```
docker-compose up -d
```
即可更新


