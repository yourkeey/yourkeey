<h1 align="center">Yurii F.</h1>

<p align="center">
  <strong>Python Backend Developer</strong> · Ukraine · Remote
</p>

<p align="center">
  I build the APIs behind Telegram checkouts and reservation workflows.<br>
  1.5+ years of commercial Python backend experience.
</p>

<p align="center">
  <a href="https://yourkeey.github.io/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-08785B?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=white"></a>
  <a href="https://yourkeey.github.io/cv.html"><img alt="Online CV" src="https://img.shields.io/badge/CV-175B78?style=for-the-badge&amp;logo=googledocs&amp;logoColor=white"></a>
  <a href="https://t.me/yourkeey"><img alt="Message me on Telegram" src="https://img.shields.io/badge/Telegram-225C9D?style=for-the-badge&amp;logo=telegram&amp;logoColor=white"></a>
</p>

<p align="center">
  <code>FastAPI</code> · <code>Django</code> · <code>PostgreSQL</code> · <code>Redis</code> · <code>pytest</code> · <code>Docker Compose</code>
</p>

## Selected work

<p align="center">
  <a href="https://yourkeey.github.io/#tea-project"><img width="44%" src="https://yourkeey.github.io/assets/projects/tea-demo-1.jpg" alt="TEA BET admin dashboard with sample orders"></a>
  <a href="https://kinshore-bay.scalo.biz/"><img width="49%" src="https://raw.githubusercontent.com/yourkeey/kinshore-bay/main/docs/media/kinshore-bay-home.jpg" alt="Kinshore Bay guest portal for a fictional resort"></a>
  <br><sub>TEA BET admin with sample data · Kinshore Bay portfolio demo</sub>
</p>

### 🍵 TEA BET · Telegram commerce

*Production client project · FastAPI, aiogram, SQLAlchemy, PostgreSQL, Redis*

Built a Telegram shop with 500+ products, a shared bot and Mini App cart, and a web admin for orders and inventory.

- Verified Telegram `initData` with HMAC-SHA256. Migrated production from SQLite to PostgreSQL and used atomic inventory checks and Redis idempotency keys to protect checkout.
- Integrated Nova Poshta tracking for manually entered waybills and added customer updates. Set up Sentry, structured logs, GitHub Actions checks, Playwright scenarios, database backups, and Docker rollback.

[Project and browser demo](https://yourkeey.github.io/#tea-project) · [Offline test report: 661 pytest tests and 1,116 smoke checks passed](https://yourkeey.github.io/verification.html)

### Kinshore Bay · Booking and reception CRM

*Hospitality reference implementation · Django, PostgreSQL, Docker Compose, pytest*

Built a guest portal and reception calendar with server-side rate and availability checks and reservation status history. The confirmation transaction locks the apartment row with `SELECT FOR UPDATE`. A test with two PostgreSQL connections checks that only one confirmation succeeds for the last available apartment.

[Source](https://github.com/yourkeey/kinshore-bay) · [Live demo](https://kinshore-bay.scalo.biz/)

### 🍯 Zimin Apiary · Online store

*Live client project · Astro, TypeScript, Cloudflare Pages*

Built a storefront for a family apiary. The checkout validates the cart, recalculates prices from the catalogue, and sends the order to the owner via Telegram.

[Live store](https://zimin-apiary.com.ua/)

## Other projects

- **Internal B2B Lead Outreach Agent** · Telegram tool for lead research and outreach drafting, built with Python and LLM APIs and deployed on Ubuntu with systemd.
- **Redmi 4A Desk Dashboard** · I turned an old Android phone into a desk display for workstation telemetry, EcoFlow readings, and Ukrainian grid outages. [Source](https://github.com/yourkeey/redmi-4a-desk-dashboard) · [Live simulation](https://yourkeey.github.io/redmi-4a-desk-dashboard/)
