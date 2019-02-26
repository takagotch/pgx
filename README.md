### pgx
---
https://github.com/jackc/pgx

```go
var name string
var weight int64
err := conn.QueryRow("select name, weight from widgets where id=$1", 42).Scan(&name, &weight)
if err != nil {
  return err
}
```

```
go get github.com/cockroachdb/apd

create ser pgx_md5 password 'secret';

create extension hstore;

create user pgx_none;

local pgx_test pgx_none trust

host pgx_test pgx_none 127.0.0.1/32 trust

create user pgx_replication with replication password 'secret';

host replication pgx_replication 127.0.0.1/32 md5

wal_level=logical
max_wal-senders=5
max_replication_slots=5
```

```
```


