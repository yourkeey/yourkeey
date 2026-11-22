# Yurii Fomenko

**Python Backend & AI Automation Developer**  
*Ukraine (Remote) · [Portfolio & Demos](https://yourkeey.github.io/) · [Telegram](https://t.me/yourkeey) · [Email](mailto:sum4ik41@gmail.com)*

```text
Backend:      Python (asyncio), FastAPI, Django, Pydantic v2, SQLAlchemy 2.0
Data & Queue: PostgreSQL 16, Redis 7, Celery
Integrations: aiogram 3 (Telegram Bot API & Mini Apps), Nova Poshta API, LLM APIs / Agents
Infra & Ops:  Docker Compose, Linux VPS (Ubuntu, systemd, Caddy/Nginx), GitHub Actions CI/CD
Quality:      pytest (fixtures and concurrency tests), Playwright, Sentry
```

---

### Featured Projects

#### 1. [TEA BET](https://yourkeey.github.io/) — Production Telegram Mini App E-Commerce Platform
- Full-cycle Telegram shop with a shared bot/Mini App cart, HMAC-SHA256 `initData` auth, atomic PostgreSQL transactions, and idempotent checkout.
- Celery background tasks, Nova Poshta shipping integration, structured JSON logging, Sentry error tracking, `pytest` coverage, and Docker rollback procedures.
- **Stack:** `FastAPI` · `aiogram 3` · `PostgreSQL 16` · `Redis 7` · `Celery` · `Docker Compose` · `Sentry`

#### 2. Kinshore Bay — HoReCa Booking & Reception CRM
- Hospitality reservation backend and reception dashboard with an interactive occupancy matrix, server-side rate validation, and strict guest check-in workflows.
- PostgreSQL `SELECT FOR UPDATE` row-level locks protect reservation confirmations from concurrent writes. Parallel tests exercise the overbooking scenario across multiple database connections.
- **Stack:** `Django` · `PostgreSQL 16` · `Docker Compose` · `pytest`

#### 3. [Workstation Telemetry & Power Outage Dashboard](https://yourkeey.github.io/redmi-4a-desk-dashboard/)
- Always-on desk monitoring ecosystem integrating EcoFlow River 2 Pro telemetry, regional power outage schedules (Ukrainian grid), and LLM session rate-limit budgets.
- Real-time battery depletion forecasting, automated power-cut countdowns, and dual-view live browser simulation (landscape smartphone dashboard + companion Telegram widget).
- **Stack:** `Python 3` · `Docker Compose` · `PowerShell` · `JavaScript (Canvas)` · `REST APIs`

---

### Engineering Standards

- **Transactional Integrity:** Row-level locks (`SELECT FOR UPDATE`), atomic database transactions, and idempotency controls for concurrent writes.
- **Test-Driven Reliability:** Extensive test coverage (unit, API integration, and concurrent race-condition scenarios) before deployment.
- **Self-Healing Infrastructure:** Containerized deployments (Docker Compose), systemd service management, persistent volumes, and rollback procedures.
