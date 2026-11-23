# Yurii F.

**Python Backend Developer**

Python backend developer with 1.5+ years of commercial experience building FastAPI APIs and asynchronous Telegram commerce workflows. I test concurrent checkouts and safe order retries, and prepare Docker releases with database backups and rollback scripts.

Ukraine · Remote · [Portfolio](https://yourkeey.github.io/) · [CV](https://yourkeey.github.io/cv.html) · [Telegram](https://t.me/yourkeey)

## Featured projects

### TEA BET · Production Telegram commerce platform

- Built a FastAPI backend for a Telegram shop with 500+ products, a shared bot and Mini App cart, and a web admin for orders and inventory.
- Verified Telegram `initData` with HMAC-SHA256, migrated production from SQLite to PostgreSQL, checked inventory in atomic transactions, and used Redis idempotency keys to prevent duplicate orders.
- Integrated Nova Poshta tracking for manually entered waybills and added customer delivery updates. Set up Sentry, structured logging, GitHub Actions checks, and Playwright scenarios.

[Project and browser demo](https://yourkeey.github.io/#tea-project) · [October 6 offline test report: 661 pytest tests and 1,116 smoke checks passed](https://yourkeey.github.io/verification.html)

### Kinshore Bay · Booking and reception CRM

- Built a Django and PostgreSQL hospitality reference implementation with a guest portal, reception calendar, server-side rate and availability checks, and reservation status history.
- Used `SELECT FOR UPDATE` on the apartment row during confirmation. A pytest scenario using two PostgreSQL connections verifies that only one confirmation succeeds for the last available apartment.

[Source](https://github.com/yourkeey/kinshore-bay) · [Live demo](https://kinshore-bay.scalo.biz/)

### Zimin Apiary · Live client storefront

Built an Astro and TypeScript store on Cloudflare Pages. The server-side checkout validates the cart, recalculates prices from the catalogue, and sends orders to the owner via Telegram.

[Live store](https://zimin-apiary.com.ua/)

## Additional engineering

- **Internal B2B Lead Outreach Agent** · Built a Telegram tool for lead research and outreach drafting with Python and LLM APIs, deployed on an Ubuntu VPS with systemd.
- **Redmi 4A Desk Dashboard** · Python service and browser dashboard for workstation telemetry, EcoFlow readings, and Ukrainian grid outage schedules. [Source](https://github.com/yourkeey/redmi-4a-desk-dashboard) · [Live simulation](https://yourkeey.github.io/redmi-4a-desk-dashboard/)

**Core stack** · Python, FastAPI, Django, SQLAlchemy, PostgreSQL, Redis, pytest, Docker Compose
