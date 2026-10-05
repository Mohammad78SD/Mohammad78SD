<p align="center">
  <img src="assets/banner.png" alt="Mohammad Sabet Daryani — Software Engineer · Python / Django" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohammadsd/"><img src="https://img.shields.io/badge/LinkedIn-mohammadsd-1B4441?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:mohammadsd2000@gmail.com"><img src="https://img.shields.io/badge/Email-mohammadsd2000%40gmail.com-1B4441?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <!-- TODO: add website badge once mimscript.com is live -->
</p>

I build Django backends and REST APIs, including real-time systems on WebSockets and Redis. I care about correctness: explicit state machines, row-level locking where concurrency matters, tests that fail when the safeguard is removed, and APIs with stable error contracts and OpenAPI docs.

I work as a software engineer and also take on freelance projects under the name MiM Script.

## Highlights

- **Concurrency-safe Django module:** lead SLA & outreach engine with row-level locking and 130 tests, including concurrency races on PostgreSQL ([leads](https://github.com/Mohammad78SD/leads)).
- **Security-hardened a Django HR system:** fixed an OTP login bypass, locked down device and admin endpoints, moved all secrets to env, added 64 tests and CI ([mahsa](https://github.com/Mohammad78SD/mahsa)).
- **Tour booking REST API:** OTP + JWT auth with throttling and attempt limits, validated reservations, 57 tests and CI ([rahorasm-backend](https://github.com/Mohammad78SD/rahorasm-backend)).

## Featured projects

| Project | What it shows |
|---|---|
| [**leads**](https://github.com/Mohammad78SD/leads) | Lead SLA and outreach module for Django (a mini-CRM). Lifecycle state machine, row-locked services (`SELECT ... FOR UPDATE`), soft delete enforced at model and queryset level, 130 tests including concurrency races on PostgreSQL, OpenAPI docs, CI. |
| [**mahsa**](https://github.com/Mohammad78SD/mahsa) | HR system in Django: attendance (RFID JSON API, correction requests, Excel export), lunch reservations, SMS/OTP login, web-push notifications, surveys and reports. Persian UI (RTL, Jalali calendar), installable as a PWA. 64 tests, CI. |
| [**rahorasm-backend**](https://github.com/Mohammad78SD/rahorasm-backend) | REST API for a tour booking platform: tours, hotels and pricing, reservations, OTP-by-SMS login with JWT (Redis-backed codes), per-tour PDF export, throttled auth endpoints. 57 tests, CI. Paired with a separate Nuxt frontend. |
| [**mimify**](https://github.com/Mohammad78SD/mimify) | WooCommerce order notifications to Telegram through a Cloudflare Worker relay, so no bot tokens or chat IDs live in WordPress. Worker tests run against an in-memory KV and a stubbed Telegram API, and CI handles releases. |
| [**lior-toolkit**](https://github.com/Mohammad78SD/lior-toolkit) | Modular WordPress/WooCommerce plugin, one file per feature, with updates delivered through GitHub Releases. Includes an auto-print queue exposed as a key-authenticated REST API. |

## Tech

<p>
  <img src="https://skillicons.dev/icons?i=python,django,fastapi,postgres,redis,docker,nginx,terraform,vue,react&theme=dark" alt="Python, Django, FastAPI, PostgreSQL, Redis, Docker, Nginx, Terraform, Vue, React">
</p>

Also: DRF · Django Channels · Celery · WebSockets · JWT · GitHub Actions

## Currently

- Software Engineer at Adlas Digital Solutions: Django, Celery, Redis and PostgreSQL in Dockerized environments.
- Completing an M.Sc. in Computer Engineering (Software).
- Building a real-time seat reservation and ticketing platform (launching soon).

## Work with me

Open to remote work and freelance projects. The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/mohammadsd/) or [email](mailto:mohammadsd2000@gmail.com).
