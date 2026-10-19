```
 _   _ ___ _    ___     ___ _  _  ___ 
| |_| |_ _| |  / _ \   |_ _| \| |/ __|
| |_| || || |_| (_) |   | || .` | (__ 
|_| |_|___|____\___/   |___|_|\_|\___|

       /\___/\
     (  -   -  )
     =( m   m )=
      )  ___  (   
     (_/     \_)
```

# Hi, I'm Mark

> Full-Stack Developer  •  Technical Co-founder  •  15+ Years Experience

```
╔══════════════════════════════════════════════════════════════╗
║  > building scalable web platforms since before it was cool  ║
║  > currently: AI-native apps, cloud-native infra, good UX    ║
╚══════════════════════════════════════════════════════════════╝
```

Pragmatic and performance-focused developer who loves building **scalable web platforms**, **cloud-native applications**, and **user-centric interfaces**. Over 15 years I've worked with global enterprises like **CBC, BMO, Ørsted, Nordea, Publicis**, and co-founded ventures in AI, fashion-tech, and price-intelligence.

---

## Tech Stack

*Versions shipped across the timeline — from jQuery-era production code to today's AI-native stack.*

```
┌──────────────────────────────────────────────────────────────────────────┐
│  FRONTEND                                             2011 ─────────► now│
│  ▸ JavaScript / TypeScript    ES5 → ES2024, TS 1.x → 5.x      2011–2026  │
│  ▸ React                      0.13 → 19                       2015–2026  │
│  ▸ Next.js                    9 → 16                          2020–2026  │
│  ▸ Angular                    2 → 19 (AngularJS 1.x before)   2013–2024  │
│  ▸ CSS / Sass → TailwindCSS   Sass, LESS → Tailwind v1 → v4   2011–2026  │
│  ▸ Shadcn UI / Radix UI       current                         2023–2026  │
│  ▸ Three.js / Recharts / D3   viz & 3D work                   2016–2026  │
│  ▸ jQuery / Backbone          legacy & ad-tech era            2011–2016  │
├──────────────────────────────────────────────────────────────────────────┤
│  MOBILE                                                                  │
│  ▸ Flutter / Dart             3.x → 3.38 (Dart 2 → 3.10)      2022–2026  │
│  ▸ Riverpod / go_router       Riverpod 1 → 3                  2022–2026  │
│  ▸ Kotlin (native Android)    services, overlays, billing     2023–2026  │
│  ▸ GLSL shaders  |  Hive      chroma-key & offline cache      2024–2026  │
├──────────────────────────────────────────────────────────────────────────┤
│  BACKEND                                                                 │
│  ▸ Node.js                    0.10 → 24 LTS                   2013–2026  │
│  ▸ Express / Restify          long-running services           2014–2026  │
│  ▸ Dart Shelf                 1.4  |  JWT auth                2024–2026  │
│  ▸ PostgreSQL                 9.x → 16                        2015–2026  │
│  ▸ MongoDB / Mongoose         3.x → 7                         2016–2026  │
│  ▸ Drizzle ORM + SQLite       current                         2024–2026  │
│  ▸ Redis  |  Centrifugo / ntfy  cache, realtime, push         2018–2026  │
├──────────────────────────────────────────────────────────────────────────┤
│  AI / ML                                                                 │
│  ▸ Anthropic Claude SDK       Claude 3 → Opus 5               2024–2026  │
│  ▸ Google Gemini  |  OpenAI   Gemini 1.5 → 3, GPT-3.5 → 5     2023–2026  │
│  ▸ FAL.ai  |  Cloudinary AI   image generation pipelines      2024–2026  │
├──────────────────────────────────────────────────────────────────────────┤
│  AUTH / PAYMENTS                                                         │
│  ▸ Passport.js → NextAuth / Clerk  |  Google & Apple Sign-In  2015–2026  │
│  ▸ Stripe                     one-off → subscriptions         2017–2026  │
│  ▸ RevenueCat / Play Billing  mobile IAP & entitlements       2024–2026  │
│  ▸ AWS SES                    transactional email at scale    2018–2026  │
├──────────────────────────────────────────────────────────────────────────┤
│  CLOUD / DEVOPS                                                          │
│  ▸ AWS                        EC2, S3, Lambda, SES            2015–2026  │
│  ▸ Docker                     1.x → 27                        2016–2026  │
│  ▸ Kubernetes  |  Azure DevOps  enterprise CI/CD              2019–2023  │
│  ▸ Coolify  |  PM2  |  Nginx  self-hosted deploys             2017–2026  │
│  ▸ Puppeteer / Playwright     scraping + E2E, on Lambda       2019–2026  │
└──────────────────────────────────────────────────────────────────────────┘
```

---

## Highlight Projects

### ⏳ [Reveller](https://reveller.app) — Founder
```
  Screen-time recovery & habit reformer
  "put the phone down, pick your life up"

  Flutter  ·  Dart Shelf API  ·  Postgres
```
- **Digital-wellbeing app** — screen-time tracking, app blocking, journaling, goals, challenges, and group accountability
- **Flutter** client (Riverpod, go_router, Freezed, fl_chart, Hive) with custom shader-driven overlay timers
- **Dart Shelf API** with **Postgres** migrations, JWT auth (access + refresh), and bcrypt password hashing
- **Realtime + notifications**: Centrifugo WebSockets, ntfy push, local notifications
- **RevenueCat** subscriptions (Reveller Plus) with server-side webhook entitlement sync
- Self-hosted on **Coolify** — Docker Compose stack for Postgres, Redis, Centrifugo, and ntfy
- Ships a reusable `asset_repository` Dart package for remote, disk-cached app assets

---

### [Poekito](https://www.poekito.com) — [Co-founder](https://github.com/TruthReveller)
```
    /\_/\      Cute pet overlays for your phone
   ( o.o )     cat · fox · corgi · deer · hare · boar
    > ^ <      ────────────────────────────────────
  ~~~~~~~~~~   floating companions + effect timers
               drawn OVER whatever app you're in
```
- **Android overlay app** — animated companions drift across the screen above any other app
- Native **Kotlin foreground service** (`SYSTEM_ALERT_WINDOW`) driven from Flutter over a `MethodChannel`
- **Chroma-keyed video rendering** — GLSL fragment shader keys "mindful cat" clips onto the system UI, mirrored in both Kotlin and Flutter
- Fullscreen effect timers (rising water, growing grass, frost, cracks) rendered natively
- **RevenueCat** one-time unlock (Poekito Plus) with a legacy Play Billing fallback path
- Remote asset delivery via the shared `reveller_asset_repository` package
- **Next.js 16 + React 19 + Tailwind v4** marketing site with Sentry

---

### [Chatelope](https://www.chatelope.com) — [Co-founder](https://github.com/TruthReveller)
```
  /\_____/\
 (  0 m 0  )   Multi-model AI chat platform — web + mobile
  \_<m>_<m>/    "talk to any AI, anywhere"
    |   |
```
- **Multi-AI hub**: Claude (Anthropic), Gemini, OpenAI, FAL.ai — all under one roof
- **Next.js 16 + React 19** frontend with TailwindCSS v4, Radix UI, Three.js
- **Drizzle ORM + SQLite** backend with Next-Auth and role-based access
- **Flutter mobile app** (Android) for on-the-go AI conversations
- PDF ingestion via PDF.js, Puppeteer scraping, local-first data with Dexie
- Real-time streaming responses, markdown rendering, code highlighting

---

### [Clothed.ai](https://clothed.ai) — Side Project
```
  +---------+      +-----------+
  |  INPUT  | ---> | CLOUDINARY| ---> AI-transformed output
  |  IMAGE  |      |   AI API  |      (restore / recolor /
  +---------+      +-----------+       remove / fill / bg)
```
- **AI image SaaS** — restore, recolor, remove objects, generative fill, background removal
- **Next.js + TypeScript** with Shadcn UI and TailwindCSS
- **MongoDB + Mongoose** for image metadata and user data
- **Clerk** auth with webhook-driven user sync
- **Stripe** payments + credit system (free tier → Pro → Premium)
- Cloudinary AI transformation pipeline with paginated community gallery

---

### [PricedOff](https://pricedoff.com) — [Co-founder](https://github.com/TruthReveller)
```
  [Amazon] ──> [Puppeteer/Playwright] ──> [Lambda+VPN]
      └──────────────────────────────────> [Watchlist]
                                           [SES alerts]
                                           [Affiliate $]
```
- Price-intelligence platform with **React + TypeScript frontend**, **Node.js + MongoDB backend**
- Chrome extension for **Amazon price tracking and watchlists**
- Scalable microservices: notification, email (SES), watchlist, and affiliate analytics
- Scraper system using **Puppeteer/Playwright + AWS Lambda + VPN rotation**

---

### [RoboLog](https://github.com/Hilo-Inc/robolog) — Hackathon
*AI-powered log monitoring system* — built for Google's **Gemma Hackathon**
- [View on Kaggle](https://www.kaggle.com/competitions/google-gemma-3n-hackathon/writeups/robolog-ai-powered-log-monitoring-system)

### [Shunido](https://www.kaggle.com/competitions/banana/writeups/shunido-virtual-fashion-exploration) — Hackathon
*Virtual fashion exploration platform* — built for Google's **Banana Hackathon**

---

## Past Roles

```
TIMELINE ──────────────────────────────────────────────────────►
  │
  ├─ Ørsted (Copenhagen)
  │   Senior Developer · Angular · Kubernetes · Azure CI/CD
  │
  ├─ Nordea (Copenhagen)
  │   Senior IT Analyst/Developer · Banking apps · Angular 9
  │
  ├─ BMO Bank of Montreal (Toronto)
  │   Senior UI Developer · Wealth & onboarding platforms
  │
  ├─ CBC (Toronto)
  │   Senior UI Developer · Media player & digital platforms
  │
  └─ Publicis (Toronto)
      Interactive Developer · React.js · Ad tech · Automation
```

---

## Connect

```
  📍  Lisbon, Portugal (Canadian)
  💼  linkedin.com/in/markobradley
  🌐  mb-hilo.github.io
  🏢  hilo.ca
```

---

## Interests

```
  🎶 bachata dancing      ✈️  travel & hackathons
  📸 photography          🍜  exploring Asian food
  💻 agentic AI coding    🤖  building with LLMs
```

---

> Always open to collaborations, hackathons, and new opportunities in **full-stack development, cloud engineering, and AI-driven products**.
