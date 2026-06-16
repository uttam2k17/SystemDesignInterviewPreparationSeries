# Databases & Storage

SQL vs NoSQL, replication, sharding, storage engines, and search.

| Topic | Depth | Article |
|-------|-------|---------|
| Developer vs architect DB thinking | Full deep-dive | [Day 7](../Day7_Databases_Developer_vs_Architect.md) |
| Database selection guide | Full deep-dive | [Day 23](../Day23_Database_Selection_System_Design.md) |
| **Search engines (Elasticsearch)** | Full deep-dive | [Search Engines Deep Dive](./Search_Engines_Elasticsearch_Deep_Dive.md) |
| Replication | Full deep-dive | [Day 30](../Day30_Database_Replication_AWS_Architecture.md) |
| Sharding | Full deep-dive | [Day 64](../Day64_Database_Sharding_Strategies.md) |
| Primary key strategies | Full deep-dive | [Day 38](../Day38_Primary_Key_Strategies_SQL_vs_NoSQL.md) |
| LSM Trees vs B-Trees | Full deep-dive | [Day 65](../Day65_LSM_Trees_vs_B_Trees.md) |
| Connection pools | Full deep-dive | [Day 47](../Day47_Database_Connection_Pool_Biggest_Blunder.md) |
| ACID vs BASE / CAP | Full deep-dive | [Day 41](../Day41_ACID_vs_BASE_Instagram_CAP.md) |
| Optimistic vs pessimistic locking | Full deep-dive | [Day 21](../Day21_Optimistic_vs_Pessimistic_Locking.md) |
| Two-phase commit | Full deep-dive | [Day 27](../Day27_Two_Phase_Commit.md) |

## Polyglot persistence cheat sheet

| Data pattern | Typical store |
|--------------|---------------|
| Transactions, joins | PostgreSQL / MySQL |
| Flexible documents | MongoDB |
| Hot cache / sessions | Redis ([Day 15](../Day15_Redis_Single_Threaded_Magic.md)) |
| Full-text search | Elasticsearch ([Search Engines](./Search_Engines_Elasticsearch_Deep_Dive.md)) |
| Write-heavy time-series | Cassandra / ScyllaDB |
| Massive event logs | Kafka + object storage |
