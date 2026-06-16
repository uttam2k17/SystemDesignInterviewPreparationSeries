# Roadmap — What's Published vs What's Planned

This repo started as a **50-day series** and has grown to **66+ days** of pattern deep-dives, failure stories, and building blocks. [Day 1](./Day1_Why_System_Design_Matters.md) originally promised **Phase 2: full "Design X" interview problems** (WhatsApp, Netflix, Uber, etc.). That phase was **partially delivered** through related pattern articles but **not** as dedicated end-to-end problem walkthroughs.

This document is the honest status board — updated so readers like Ayush know what's here and what's coming.

---

## ✅ Published (66 days + chapter deep-dives)

All `DayN_*.md` files at repo root are **full deep-dives**. Browse by topic:

| Chapter | Index |
|---------|-------|
| Fundamentals | [fundamentals/README.md](./fundamentals/README.md) |
| Load balancing | [fundamentals/load-balancing.md](./fundamentals/load-balancing.md) |
| Message queues | [message-queues/README.md](./message-queues/README.md) |
| RabbitMQ deep dive | [message-queues/RabbitMQ_Deep_Dive.md](./message-queues/RabbitMQ_Deep_Dive.md) |
| Databases | [databases/README.md](./databases/README.md) |
| Search engines | [databases/Search_Engines_Elasticsearch_Deep_Dive.md](./databases/Search_Engines_Elasticsearch_Deep_Dive.md) |
| Caching & Redis | [caching/README.md](./caching/README.md) |
| Distributed systems | [distributed-systems/README.md](./distributed-systems/README.md) |
| Security & auth | [security-auth/README.md](./security-auth/README.md) |
| Deployment | [deployment/README.md](./deployment/README.md) |
| Interview problems | [interview-problems/README.md](./interview-problems/README.md) |

---

## 🔜 Planned — Full "Design X" Problems (P0)

| # | Problem | Why it matters |
|---|---------|----------------|
| 1 | **URL Shortener** | Most common warm-up; base62, redirects, analytics |
| 2 | **News Feed / Twitter** | Fan-out on write vs read; celebrity problem |
| 3 | **WhatsApp / Chat** | WebSocket gateway, presence, delivery receipts |
| 4 | **Uber / Ride matching** | Geospatial index (geohash / H3 / quadtree) |
| 5 | **YouTube / Netflix** | Upload, transcode, CDN, adaptive bitrate |
| 6 | **Typeahead / Autocomplete** | Trie, top-k, precomputed rankings |
| 7 | **Ticketmaster** | Seat holds, inventory, oversell race |
| 8 | **Google Drive sync** | Chunking, dedup, conflict resolution |
| 9 | **Distributed KV (Dynamo)** | Quorum, vector clocks, anti-entropy |
| 10 | **Swiggy / Zomato** | Multi-sided marketplace, dispatch, ETA |

---

## 🔜 Planned — Concept Deep-Dives (from reader feedback)

| Topic | Chapter | Status |
|-------|---------|--------|
| CDN internals | fundamentals / deployment | 🔜 Planned |
| WebSockets vs SSE vs Long Polling | fundamentals | 🔜 Planned |
| CAP → PACELC | distributed-systems | 🔜 Planned |
| Raft / consensus simplified | distributed-systems | 🔜 Planned |
| WAL deep-dive | databases | 🔜 Planned |
| CDC & Event Sourcing / CQRS | message-queues | 🔜 Planned |
| API Gateway vs Service Mesh | fundamentals | 🔜 Planned |
| Cursor pagination at scale | databases | 🔜 Planned |
| Kafka standalone deep-dive | message-queues | 🔜 Planned (comparison exists: Day 36) |

---

## 📁 Repo layout note

- **Day articles** stay at repo root (`Day1_…` through `Day66_…`) so existing links from YouTube, LinkedIn, and bookmarks **keep working**.
- **Topic folders** (`fundamentals/`, `message-queues/`, `databases/`, etc.) are **indexes + new chapter-only deep-dives** that don't fit a single Day number.
- If you expected a folder and found only a README link — the full article is usually the linked `DayN` file at root. New chapter files (e.g. RabbitMQ Deep Dive) live inside the folder.

---

## 🗳️ Vote for what ships next

Open a GitHub issue with the label `topic-request` or comment on the repo. Priority follows reader demand.

*Last updated: June 2026*
