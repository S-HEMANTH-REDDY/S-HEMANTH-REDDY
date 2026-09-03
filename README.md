# Hemanth Reddy Sankaramaddi

**Software Engineer (Backend / Distributed Systems) + AI Engineer · MS CS, University of Florida (May 2026)**

I build distributed backend systems and applied-ML pipelines end to end — event-driven
microservices in Go, high-throughput real-time services, performance-critical C++, and
production computer-vision models. First-author on two peer-reviewed CV/AI papers from
UF's IFAS Precision Agriculture Lab.

Open to full-time roles in backend, distributed systems, and ML/AI engineering.

📧 hemanth1729hr@gmail.com &nbsp;·&nbsp;
[LinkedIn](https://linkedin.com/in/hemanth-reddy-uf) &nbsp;·&nbsp;
[Portfolio](https://s-hemanth-reddy.github.io/Portfolio/) &nbsp;·&nbsp;
[Google Scholar](https://scholar.google.com/citations?user=YOUR_ID)

---

### What I build

**Distributed backends.** Go microservices, Kafka event pipelines with idempotent
consumers and at-least-once delivery, Redis caching, PostgreSQL schema and query
design. Built services sustaining thousands of concurrent connections and
multi-thousand-event/sec throughput, tuned under k6 / load-generator tests.

**Applied ML & computer vision.** PyTorch pipelines for real-world agricultural vision
— 2D-to-3D reconstruction and CNN-LSTM time-series detection. Two first-author papers
(2026). Also profiling ML hot paths and reimplementing them in C++17 for measured
multi-x latency wins.

**Systems & performance.** Multithreaded C++ over TCP, fault-tolerant containerized
worker pools, CI/CD with GitHub Actions, observability with Prometheus / Grafana.

---

### Featured work

| Project | What it is | Stack |
|---|---|---|
| **feed-engine** | Distributed Reddit-style feed backend — ingest, ranking, fan-out; idempotent consumers, ~3.2k events/sec on a 3-broker cluster | Go · Kafka · Redis · PostgreSQL |
| **quick-chat** | Real-time chat service — 5k concurrent connections, 8.5k msg/sec, p99 42 ms under load | Go · WebSockets · Redis Pub/Sub |
| **llm-inference-runtime** | LLM inference runtime — KV cache & continuous batching | Python · PyTorch · CUDA |
| **gpu-kernels-dl** | Custom GPU kernels: tiled matmul, row-wise softmax, parallel reduction, benchmarked vs PyTorch | Triton · CUDA C++ |
| **banking-systems** | Backend banking system modeling accounts, transactions, transfers | C++ |
| **file-transfer-system** | Multithreaded client-server file transfer over TCP | C++ |

---

### Selected research

- **2D-to-3D Image Reconstruction in Agriculture: A Review of Methods, Challenges, and
  AI-Driven Opportunities.** Sankaramaddi, H., Lee, W. S., & Kim, K. *Sensors* 26(6), 2026.
- **Time-Series Detection of Leaf Wetness Using a CNN-LSTM-Based Vision System in
  Strawberry Farming.** Sankaramaddi, H., Lee, W. S., & Peres, N. A. *J. Biosyst. Eng.*
  51(1), 19, 2026.

---

### Core stack

**Languages** Go · Python · Java · C++17 · TypeScript · SQL
**Backend** FastAPI · Spring Boot · gRPC · REST · WebSockets · Kafka · Redis
**Data** PostgreSQL · MySQL · MongoDB
**ML** PyTorch · OpenCV · NumPy
**Infra** Docker · AWS · GitHub Actions · Prometheus · Grafana · Linux
