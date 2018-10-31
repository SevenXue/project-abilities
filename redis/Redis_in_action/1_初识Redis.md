# 初识Redis
## Redis简介
1.  redis是内存数据库
2.  redis可以存储键（key）与5种不同类型的值（value）之间的映射（mapping）。
3.  redis有两种不同形式的持久化方法，都可以用小而紧凑的格式将存储在内存中的数据写入硬盘：  
时间点转储or修改数据库的命令都写入一个只追加文件里面；
## Redis数据结构简介
1. String字符串  
GET、SET、DEL
2. List列表  
RPUSH、 LRANGE、 LINDEX、 LPOP
3. SET集合  
SADD、 SMEMBERS、 SISMEMBER、 SREM
4. Hash散列  
HSET、HGET、 HGETALL、 HDEL
5. Zset有序集合  
ZDD、 ZRANGE、 ZRANGEBYSCORE、 ZREM
## 你好redis
使用python连接redis
