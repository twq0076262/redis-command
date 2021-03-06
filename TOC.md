 - Key（键）
   - [DEL](key/del.md)
   - [DUMP](key/dump.md)
   - [EXISTS](key/exists.md)
   - [EXPIRE](key/expire.md)
   - [EXPIREAT](key/expireat.md)
   - [KEYS](key/keys.md)
   - [MIGRATE](key/migrate.md)
   - [MOVE](key/move.md)
   - [OBJECT](key/object.md)
   - [PERSIST](key/persist.md)
   - [PEXPIRE](key/pexpire.md)
   - [PEXPIREAT](key/pexpireat.md)
   - [PTTL](key/pttl.md)
   - [RANDOMKEY](key/randomkey.md)
   - [RENAME](key/rename.md)
   - [RENAMENX](key/renamenx.md)
   - [RESTORE](key/restore.md)
   - [SORT](key/sort.md)
   - [TTL](key/ttl.md)
   - [TYPE](key/type.md)
   - [SCAN](key/scan.md)
 - String（字符串）
   - [APPEND](string/append.md)
   - [BITCOUNT](string/bitcount.md)
   - [BITOP](string/bitop.md)
   - [DECR](string/decr.md)
   - [DECRBY](string/decrby.md)
   - [GET](string/get.md)
   - [GETBIT](string/getbit.md)
   - [GETRANGE](string/getrange.md)
   - [GETSET](string/getset.md)
   - [INCR](string/incr.md)
   - [INCRBY](string/incrby.md)
   - [INCRBYFLOAT](string/incrbyfloat.md)
   - [MGET](string/mget.md)
   - [MSET](string/mset.md)
   - [MSETNX](string/msetnx.md)
   - [PSETEX](string/psetex.md)
   - [SET](string/set.md)
   - [SETBIT](string/setbit.md)
   - [SETEX](string/setex.md)
   - [SETNX](string/setnx.md)
   - [SETRANGE](string/setrange.md)
   - [STRLEN](string/strlen.md)
 - Hash（哈希表）
   - [HDEL](hash/hdel.md)
   - [HEXISTS](hash/hexists.md)
   - [HGET](hash/hget.md)
   - [HGETALL](hash/hgetall.md)
   - [HINCRBY](hash/hincrby.md)
   - [HINCRBYFLOAT](hash/hincrbyfloat.md)
   - [HKEYS](hash/hkeys.md)
   - [HLEN](hash/hlen.md)
   - [HMGET](hash/hmget.md)
   - [HMSET](hash/hmset.md)
   - [HSET](hash/hset.md)
   - [HSETNX](hash/hsetnx.md)
   - [HVALS](hash/hvals.md)
   - [HSCAN](hash/hscan.md)
 - List（列表）
   - [BLPOP](list/blpop.md)
   - [BRPOP](list/brpop.md)
   - [BRPOPLPUSH](list/brpoplpush.md)
   - [LINDEX](list/lindex.md)
   - [LINSERT](list/linsert.md)
   - [LLEN](list/llen.md)
   - [LPOP](list/lpop.md)
   - [LPUSH](list/lpush.md)
   - [LPUSHX](list/lpushx.md)
   - [LRANGE](list/lrange.md)
   - [LREM](list/lrem.md)
   - [LSET](list/lset.md)
   - [LTRIM](list/ltrim.md)
   - [RPOP](list/rpop.md)
   - [RPOPLPUSH](list/rpoplpush.md)
   - [RPUSH](list/rpush.md)
   - [RPUSHX](list/rpushx.md)
 - Set（集合）
   - [SADD](set/sadd.md)
   - [SCARD](set/scard.md)
   - [SDIFF](set/sdiff.md)
   - [SDIFFSTORE](set/sdiffstore.md)
   - [SINTER](set/sinter.md)
   - [SINTERSTORE](set/sinterstore.md)
   - [SISMEMBER](set/sismember.md)
   - [SMEMBERS](set/smembers.md)
   - [SMOVE](set/smove.md)
   - [SPOP](set/spop.md)
   - [SRANDMEMBER](set/srandmember.md)
   - [SREM](set/srem.md)
   - [SUNION](set/sunion.md)
   - [SUNIONSTORE](set/sunionstore.md)
   - [SSCAN](set/sscan.md)
 - SortedSet（有序集合）
   - [ZADD](sorted_set/zadd.md)
   - [ZCARD](sorted_set/zcard.md)
   - [ZCOUNT](sorted_set/zcount.md)
   - [ZINCRBY](sorted_set/zincrby.md)
   - [ZRANGE](sorted_set/zrange.md)
   - [ZRANGEBYSCORE](sorted_set/zrangebyscore.md)
   - [ZRANK](sorted_set/zrank.md)
   - [ZREM](sorted_set/zrem.md)
   - [ZREMRANGEBYRANK](sorted_set/zremrangebyrank.md)
   - [ZREMRANGEBYSCORE](sorted_set/zremrangebyscore.md)
   - [ZREVRANGE](sorted_set/zrevrange.md)
   - [ZREVRANGEBYSCORE](sorted_set/zrevrangebyscore.md)
   - [ZREVRANK](sorted_set/zrevrank.md)
   - [ZSCORE](sorted_set/zscore.md)
   - [ZUNIONSTORE](sorted_set/zunionstore.md)
   - [ZINTERSTORE](sorted_set/zinterstore.md)
   - [ZSCAN](sorted_set/zscan.md)
   - [ZRANGEBYLEX](sorted_set/zrangebylex.md)
   - [ZLEXCOUNT](sorted_set/zlexcount.md)
   - [ZREMRANGEBYLEX](sorted_set/zremrangebylex.md)
 - HyperLogLog
   - [PFADD](hyperloglog/pfadd.md)
   - [PFCOUNT](hyperloglog/pfcount.md)
   - [PFMERGE](hyperloglog/pfmerge.md)
 - Pub/Sub（发布/订阅）
   - [PSUBSCRIBE](pub_sub/psubscribe.md)
   - [PUBLISH](pub_sub/publish.md)
   - [PUBSUB](pub_sub/pubsub.md)
   - [PUNSUBSCRIBE](pub_sub/punsubscribe.md)
   - [SUBSCRIBE](pub_sub/subscribe.md)
   - [UNSUBSCRIBE](pub_sub/unsubscribe.md)
 - Transaction（事务）
   - [DISCARD](transaction/discard.md)
   - [EXEC](transaction/exec.md)
   - [MULTI](transaction/multi.md)
   - [UNWATCH](transaction/unwatch.md)
   - [WATCH](transaction/watch.md)
 - Script（脚本）
   - [EVAL](script/eval.md)
   - [EVALSHA](script/evalsha.md)
   - [SCRIPT EXISTS](script/script_exists.md)
   - [SCRIPT FLUSH](script/script_flush.md)
   - [SCRIPT KILL](script/script_kill.md)
   - [SCRIPT LOAD](script/script_load.md)
 - Connection（连接）
   - [AUTH](connection/auth.md)
   - [ECHO](connection/echo.md)
   - [PING](connection/ping.md)
   - [QUIT](connection/quit.md)
   - [SELECT](connection/select.md)
 - Server（服务器）
   - [BGREWRITEAOF](server/bgrewriteaof.md)
   - [BGSAVE](server/bgsave.md)
   - [CLIENT GETNAME](server/client_getname.md)
   - [CLIENT KILL](server/client_kill.md)
   - [CLIENT LIST](server/client_list.md)
   - [CLIENT SETNAME](server/client_setname.md)
   - [CONFIG GET](server/config_get.md)
   - [CONFIG RESETSTAT](server/config_resetstat.md)
   - [CONFIG REWRITE](server/config_rewrite.md)
   - [CONFIG SET](server/config_set.md)
   - [DBSIZE](server/dbsize.md)
   - [DEBUG OBJECT](server/debug_object.md)
   - [DEBUG SEGFAULT](server/debug_segfault.md)
   - [FLUSHALL](server/flushall.md)
   - [FLUSHDB](server/flushdb.md)
   - [INFO](server/info.md)
   - [LASTSAVE](server/lastsave.md)
   - [MONITOR](server/monitor.md)
   - [PSYNC](server/psync.md)
   - [SAVE](server/save.md)
   - [SHUTDOWN](server/shutdown.md)
   - [SLAVEOF](server/slaveof.md)
   - [SLOWLOG](server/slowlog.md)
   - [SYNC](server/sync.md)
   - [TIME](server/time.md)