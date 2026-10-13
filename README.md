### Mahir Chinwala

ECE at BITS Pilani Goa. I work on backend and distributed systems in Go and Java, plus GPU performance in CUDA.

| Project | What it is | Proof |
|---|---|---|
| **[Watermark](https://github.com/extrem21/watermark)** | Crash-safe Postgres CDC pipeline in Go | **50/50** seeded `SIGKILL` crashes recovered to exact row equality · **2,396** changes/s at **34 ms** p99 |
| **[Ledger](https://github.com/extrem21/ledger)** | Idempotent order service with a transactional outbox (Java, Spring Boot) | **50** concurrent retries → exactly one order · drain scales **308 → 1,153** events/s on 4 workers |
| **Probe** | GPU hash and sort-merge join engine (CUDA C++) | **91%** of peak DRAM bandwidth, within **4%** of CUB · radix sort at **2.1B** keys/s on a T4 |

**ML Infrastructure Intern, Pragya AI** (2026): deployed the inference service for a video-model demo used by **1000+ researchers**. Cut cold start from **33 s to 6 s** and failed runs from **11% to 2%**.

**Stack:** Go · Java · C++ · CUDA · Python · PostgreSQL · Linux · Docker

[LinkedIn](https://linkedin.com/in/mahir-chinwala) · mahirchinwala95@gmail.com
