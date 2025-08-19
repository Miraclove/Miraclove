# Hi, I'm **Weizhi Peng** (Miraclove)

**Software Developer & Machine Learning Engineer — building high‑efficiency AI applications**

[Website](https://pengwz.info) · [GitHub](https://github.com/Miraclove) · [LinkedIn](https://www.linkedin.com/in/weizhi-peng-uk/) · Email: jimpeng98 \[at] gmail.com · Ontario, Canada

---

## 🚀 What I Do

* **LLM engineering & inference**: train, fine‑tune, quantize, and ship language models to production (PyTorch · DeepSpeed · vLLM).
* **Full‑stack product engineering**: React/Next.js front‑ends; **Django/DRF** & **FastAPI** back‑ends on Docker; Postgres/Redis; CI/CD.
* **AI application platforms**: REST/gRPC model services, VS Code extensions, and integrations that turn models into products.
* **Data & ML Ops**: reproducible pipelines, evaluation harnesses, and monitoring to make models useful, fast, and reliable.
* **Applied ML in finance**: transformer‑based time‑series forecasting and HFT‑oriented model integration.

## ✨ Highlights

* Led development of a **20B‑parameter code‑completion LLM** and **shipped Copilot‑style IDE assistance** (VS Code extension + chat).
* **60% faster training** on multi‑A100 clusters via DeepSpeed/Accelerate optimizations; automated distributed training & eval.
* Productionized LLM APIs with **FastAPI on Docker**; deployed low‑latency serving with **vLLM**.
* Built **transformer/GPT/BERT** models for **high‑frequency trading**, integrated into real‑time systems and dashboards.

## 🧰 Tech Toolbox

**Full-stack, Python, Java, JavaScript/TypeScript, PyTorch, DeepSpeed, Accelerate, vLLM, FastAPI, Django/DRF, React/Next.js, Docker, Linux, SQL/PostgreSQL, Redis, CUDA (basics), pandas, Git, AWS/GCP, VS Code API**

### 🧱 Full‑Stack Quick Hits

* Frontend: React/Next.js, Tailwind; dashboards for model telemetry and admin.
* Backend: Django/DRF and FastAPI on Docker; auth/RBAC, rate limiting; CI/CD.
* Data: PostgreSQL, Redis; background jobs with Celery/RQ.
* **Java**: desktop apps & backend services; networking (sockets/NIO), concurrency; built a **Skype‑style IM(AIDA)** client in Java (login, friend list, messaging, file transfer).

---

## 🔧 Featured Projects

* **DevAssistant** — AI pair‑programmer for your company APIs

  * 20B LLM for code‑completion + fine‑tuned chat; **VS Code extension** for inline suggestions & API‑aware Q\&A.
  * Low‑latency serving (vLLM), REST backend (FastAPI/Docker), custom evaluation for accuracy/speed.
  * **React/Next.js dashboard** for prompt management, logs, and evaluation reports.

* **miraclove.github.io** — Personal site & tech notes — Personal site & tech notes

  * Writing on LLM engineering, efficient training, and applied ML.

* **WUDictionary (C++)** — Lightweight Chinese↔English dictionary

* **AIDA(Skype‑style IM using Java)** — Desktop instant‑messaging client written in **Java**, similar to Skype; supports login, friend lists, real‑time messaging, and file transfer.

> Want a deep dive or demo video? Ping me — I’m happy to share architecture diagrams and benchmarks.

---

## 💼 Experience (selected)

* **Machine Learning Engineer Intern — Shengqu Games**

  * Trained/served **20B LLM** for code completion; delivered a **VS Code extension** for real‑time assistance.
  * Optimized distributed training (**DeepSpeed/Accelerate**, 4×A100), shipped **FastAPI** microservices on Docker, and built a **custom evaluator**.
  * Built internal **Django/DRF** admin services (jobs, metrics, auth) and a **React** dashboard for telemetry & A/B evals.

* **Quant ML Intern — BOC International (Fintech)**

  * Designed transformer‑based models for **market forecasting**; improved predictive accuracy and integrated into **HFT** systems.
  * Built **React** dashboards, Python/SQL data pipelines, and backtesting frameworks for model validation.
  * Exposed strategies and analytics via **Django/DRF** APIs for downstream tools.

---

## 📚 Recent Focus

* Long‑context inference; structured tool‑use and multi‑step planners.
* Cost control: quantized serving, distillation, cache hits; autoscaling.
* Data flywheel: feedback loops from production traces → eval datasets → fine‑tuning.
* UX patterns: streaming responses, inline edits, fallbacks, human‑in‑the‑loop review.

## 🏛️ Education

* **MSc, Artificial Intelligence — King’s College London**
* **BSc, Computer Science (First Class Honours) — University of Birmingham**

---

## 🤝 Open to

**AI product engineering · LLM platform/inference · ML infra · quant ML/analytics · developer tooling**

If your team ships models that real users touch, I’d love to chat.

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Miraclove\&show_icons=true\&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Miraclove\&layout=compact)

![Streak](https://github-readme-streak-stats.herokuapp.com/?user=Miraclove)

---

### How I Work

* **Measure first**: define task‑level metrics & benchmarks before training.
* **Ship small, iterate**: staged rollouts with tracing/monitoring; automate everything that repeats.
* **Make it fast**: profile → optimize kernels/IO → caching/quantization → scale‑out only when needed.

> *“Useful, reliable, fast — in that order.”*