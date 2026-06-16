# Message Queues & Event Streaming

Async communication, job scheduling, and event-driven architecture.

| Topic | Depth | Article |
|-------|-------|---------|
| **RabbitMQ deep dive** | Full deep-dive | [RabbitMQ Deep Dive](./RabbitMQ_Deep_Dive.md) |
| RabbitMQ vs Kafka (decision guide) | Full deep-dive | [Day 36](../Day36_RabbitMQ_vs_Kafka_Architects_Decision_Guide.md) |
| Distributed job scheduler (RabbitMQ spine) | Full deep-dive | [Day 62](../Day62_Distributed_Job_Scheduler_RabbitMQ.md) |
| Outbox pattern | Full deep-dive | [Day 39](../Day39_Outbox_Pattern_Reliable_Messaging.md) |
| Kafka schema evolution | Full deep-dive | [Day 31](../Day31_Kafka_Schema_Evolution_New_Topic_Strategy.md) |
| Kafka partition assignment | Full deep-dive | [Day 34](../Day34_Kafka_Partition_Assignment_And_Rebalancing.md) |
| Kafka message ordering | Full deep-dive | [Day 46](../Day46_Kafka_Message_Ordering_Partitions_Architects_Know.md) |
| Kafka OOM duplicate charge | War story | [Day 49](../Day49_Kafka_OOM_Crash_Duplicate_Charge_Idempotency.md) |

## Quick pick guide

| You need… | Start here |
|-----------|------------|
| Per-message ACK, DLQ, job scheduling | [RabbitMQ Deep Dive](./RabbitMQ_Deep_Dive.md) |
| RabbitMQ **or** Kafka? | [Day 36](../Day36_RabbitMQ_vs_Kafka_Architects_Decision_Guide.md) |
| High-throughput event log + replay | Day 36 → then Kafka days (31, 34, 46) |
| Reliable publish without 2PC | [Day 39 Outbox](../Day39_Outbox_Pattern_Reliable_Messaging.md) |
