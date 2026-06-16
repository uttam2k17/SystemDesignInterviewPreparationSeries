# Load Balancing — Topic Hub

> **Full deep-dive:** [Day 8 — Load Balancing: Traffic Orchestration](../Day8_Load_Balancing.md)

Load balancing is how you spread traffic across multiple servers so no single machine becomes the bottleneck. Every "Design X at scale" answer eventually needs one.

## What you'll learn in the full article

| Section | Covers |
|---------|--------|
| **Why it exists** | Single-server limits, failover, horizontal scaling |
| **Layer 4 vs Layer 7** | TCP passthrough vs HTTP-aware routing |
| **Algorithms** | Round-robin, weighted, least connections, least response time, consistent hashing |
| **Health checks** | Active vs passive; why unhealthy nodes must be drained |
| **Sticky sessions** | When you need them (and why they're usually a smell) |
| **Global load balancing** | DNS, anycast, geo-routing |

## Architect's one-liner

> **A load balancer is a traffic cop in front of your fleet — it picks which backend handles each request, removes dead nodes, and lets you scale horizontally without the client knowing there are many servers.**

## When to mention it in an interview

- Any design with **>1 app server** (almost always)
- When asked about **high availability** or **zero-downtime deploys** (pairs with [Day 42 Blue-Green](../Day42_Blue_Green_Deployment_Zero_Downtime.md))
- When a **hot key** or celebrity user breaks even hashing ([Day 64 Sharding](../Day64_Database_Sharding_Strategies.md))

## Related topics

| Topic | Link |
|-------|------|
| Reverse proxy / API gateway | [Day 29](../Day29_Forward_Reverse_Proxy.md) |
| Consistent hashing (session affinity) | [Day 28](../Day28_Consistent_Hashing_Resharding.md) |
| Rate limiting at the edge | [Day 57](../Day57_Rate_Limiting_Algorithms_Fixed_Window_Boundary_Bug.md) |
| Kubernetes scaling | [Day 11](../Day11_Kubernetes_Scaling.md) |

---

**→ Read the complete article:** [Day 8 — Load Balancing](../Day8_Load_Balancing.md)
