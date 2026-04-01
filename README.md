# Data Engineering Roadmap — Zero to Architect

> An opinionated, structured path from complete beginner to senior data engineer.  
> Built for the UK/EU job market. No fluff, no detours.

🔗 **[View the live roadmap →](https://YOUR-USERNAME.github.io/data-engineering-roadmap)**

---

## What this is

A career roadmap for anyone starting from scratch in data engineering, structured into 7 phases plus an expert tier. Each phase has a clear outcome, a curated learning list, a coach's note explaining *why* things are ordered this way, and mandatory portfolio projects.

The roadmap is opinionated by design. It tells you what to learn, what to skip, and what order actually works — based on what UK/EU employers hire for.

---

## Phases at a glance

| Phase | Focus | Timeline |
|---|---|---|
| 1 | Core Foundations (Python, SQL, Data Modeling, Git) | Month 0–2 |
| 2 | Modern Infrastructure (Docker, Distributed thinking, Object Storage) | Month 2–3 |
| 3 | Spark & Delta Lake — the engine room | Month 3–6 |
| 4 | Orchestration & Analytics Stack (Airflow, dbt) | Month 6–9 |
| 5 | Cloud Specialization (Azure **or** AWS — pick one) | Month 9–12 |
| 6 | Streaming & Real-Time (Kafka, Spark Structured Streaming) | Month 12–15 |
| Expert+ | Senior & Architect Differentiators (DataOps, FinOps, CI/CD) | Month 15+ |

---

## Key design decisions

**Data Modeling is in Phase 1.** Most roadmaps bury this or skip it. You can't build a reliable lakehouse if you don't know what a star schema is.

**Hadoop is treated as legacy.** You learn the concepts (HDFS, MapReduce) to understand *why* Spark exists — then move immediately to Object Storage (S3/ADLS), which is what you'll actually use.

**Kafka is in Phase 6, not Phase 2.** Streaming is Hard Mode. Engineers who learn Kafka before they understand idempotent batch pipelines always struggle. Batch first, streaming second.

**One cloud, not three.** Learning Azure, AWS, and GCP simultaneously leads to shallow knowledge in all three. Pick one, go deep. A second cloud takes weeks once you know one well — the concepts transfer.

**The Expert tier is not optional extras.** Data Quality, CI/CD for data, and FinOps are what separate junior engineers from senior ones in every interview. They have dedicated project work.

---

## How to use this

1. Work through the phases in order — the sequencing is intentional
2. Complete every portfolio project before moving to the next phase
3. Read the "Coach's Note" in each phase — it explains *why* things are ordered this way
4. Use the "What good looks like" section to self-assess before moving on

---

## Running locally

It's a single HTML file with no dependencies.

```bash
git clone https://github.com/YOUR-USERNAME/data-engineering-roadmap.git
cd data-engineering-roadmap
open index.html   # macOS
# or: start index.html (Windows)
# or: xdg-open index.html (Linux)
```

---

## Hosting on GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select `main` branch and `/ (root)` folder
4. Click **Save**
5. Your site will be live at `https://YOUR-USERNAME.github.io/data-engineering-roadmap` within a minute or two

---

## Contributing

Spotted something wrong? Know a better tool for a phase? Open an issue or PR. The roadmap is opinionated but not closed to improvement — especially as the ecosystem evolves.

---

## License

MIT — do whatever you want with it. If you find it useful, a ⭐ is appreciated.
