# clickhouse-partition-cleaner

```
USAGE:
   clickhouse-partition-cleaner [arguments...]

ARGUMENTS:
   --host          server host (default: "127.0.0.1")
   --port          server port (default: "9000")
   --user,     -u  user name (default: "default")
   --database, -d  database (default: "default")
   --table,    -t  table (default: "test")
   --parts,    -p  the number of last partitions that will not be deleted (default: "10")
   --dry-run,  -n  do not apply cleaning, only show partitions to clean out
```
