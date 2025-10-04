# redis-tutorial
Redisとmemtier_benchmarkで遊ぶ

## 実行コマンド
```bash
docker-compose up -d
docker exec -it redis-7000 redis-cli --cluster create \
  redis-7000:7000 \
  redis-7001:7001 \
  redis-7002:7002 \
  redis-7003:7003 \
  redis-7004:7004 \
  redis-7005:7005 \
  --cluster-replicas 1
```
