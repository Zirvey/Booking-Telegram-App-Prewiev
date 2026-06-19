<div align="center">

# Telegram Booking Bot & Mini App

**Turn Telegram into your booking system — no website, no messy DMs, no missed appointments.**

Ready-to-launch solution for freelancers, trainers, tutors, barbers, therapists, and any appointment-based business.

<br>

![Hero Banner](docs/screenshots/general/hero-banner.png)

<br>

[![Request Demo](https://img.shields.io/badge/Request_Demo-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](#contact)
[![Status](https://img.shields.io/badge/Status-Ready_to_Launch-22C55E?style=for-the-badge)](#packages)
[![Stack](https://img.shields.io/badge/Stack-Telegram_Mini_App-6366F1?style=for-the-badge)](#tech-stack)

</div>

---

## Built for Real Businesses

| Niche | Use case |
|-------|----------|
| **Personal trainers** | Session booking, packages, reminders |
| **Barbers & salons** | Service-based slots, premium branded UI |
| **Tutors & teachers** | Lesson scheduling, parent-friendly flow |
| **Therapists & consultants** | Calm booking experience, online sessions |
| **Beauty & wellness** | Treatments, memberships, no-show reduction |
| **Freelancers** | Professional intake without a separate website |

> **Your client books in 2–3 taps — while competitors still reply in DMs.**

---

## White-Label by Niche

Each client gets a **unique look and feel** — not a generic template.

### Personal Trainer — energetic, bold

<table>
  <tr>
    <td width="280"><img src="docs/screenshots/niches/trainer-booking.png" alt="Trainer booking screen" width="260"></td>
    <td>
      <b>FitPro Training</b><br>
      Dark UI + orange accents · 60-min sessions · package support<br><br>
      Perfect for coaches, gyms, and fitness studios.
    </td>
  </tr>
</table>

### Barber — premium, masculine

<table>
  <tr>
    <td width="280"><img src="docs/screenshots/niches/barber-booking.png" alt="Barber booking screen" width="260"></td>
    <td>
      <b>Iron & Blade Barbers</b><br>
      Black & gold aesthetic · service picker (Haircut, Beard, Combo)<br><br>
      Built for barbershops and grooming brands.
    </td>
  </tr>
</table>

### Tutoring — clean, academic

<table>
  <tr>
    <td width="280"><img src="docs/screenshots/niches/tutor-booking.png" alt="Tutor lesson booking screen" width="260"></td>
    <td>
      <b>BrightMinds Tutoring</b><br>
      Sky blue education UI · subject tags · flexible lesson slots<br><br>
      Ideal for tutors, language teachers, and online schools.
    </td>
  </tr>
</table>

### Beauty & Wellness — elegant, soft

<table>
  <tr>
    <td width="280"><img src="docs/screenshots/niches/beauty-booking.png" alt="Beauty salon booking screen" width="260"></td>
    <td>
      <b>Luna Glow Studio</b><br>
      Blush & cream palette · treatment list with durations<br><br>
      For salons, spas, and beauty professionals.
    </td>
  </tr>
</table>

### Counseling — calm, trustworthy

<table>
  <tr>
    <td width="280"><img src="docs/screenshots/niches/consulting-booking.png" alt="Counseling session booking screen" width="260"></td>
    <td>
      <b>MindSpace Counseling</b><br>
      Sage green wellness UI · individual, couples, online sessions<br><br>
      For psychologists, coaches, and consultants.
    </td>
  </tr>
</table>

---

## How It Works in Telegram

Clients never leave Telegram. The bot handles entry points and notifications; the Mini App handles the booking UI.

<table>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/telegram/bot-conversation.png" alt="Telegram bot conversation with booking menu" width="260"><br>
      <b>Bot menu & booking</b><br>
      <sub>/start → Book Appointment → Mini App opens → confirmation in chat</sub>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/telegram/reminders.png" alt="Telegram automated appointment reminders" width="260"><br>
      <b>Automated reminders</b><br>
      <sub>24h and 2h before appointment — sent automatically by the bot</sub>
    </td>
  </tr>
</table>

**Typical flow:**
1. Client opens your bot and taps **Book Appointment**
2. Mini App opens with your branded calendar
3. Client picks a slot and confirms
4. Bot sends confirmation in chat
5. Reminders go out automatically before the visit

---

## Client & Admin Screens

<table>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/general/my-bookings.png" alt="My bookings screen" width="260"><br>
      <b>My Bookings</b><br>
      <sub>Upcoming visits across all service types</sub>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/general/admin-panel.png" alt="Admin panel dashboard" width="260"><br>
      <b>Admin Panel</b><br>
      <sub>Slots, stats, bulk creation, manual booking</sub>
    </td>
  </tr>
</table>

---

## Problem → Solution

| Before | After |
|--------|-------|
| Endless DM scheduling | Structured booking in Telegram |
| Clients forget appointments | Auto reminders at 24h and 2h |
| Schedule in notes or Excel | Admin panel with live stats |
| No package sales | Single sessions + subscription packages |
| Generic chat experience | Branded Mini App per niche |

---

## What's Included

- **Telegram Bot** — menu, commands, push notifications
- **Telegram Mini App** — booking UI with niche-specific branding
- **Admin panel** — slot management, manual booking, stats
- **Auto reminders** — 24h and 2h before appointment
- **Cancellation rules** — configurable cutoff (e.g. 24h)
- **Packages** — single bookings + session bundles
- **White-label** — name, copy, prices, currency, timezone
- **Google Calendar** — optional sync

---

## System Flow

```mermaid
flowchart LR
    A[Client opens bot] --> B[Mini App: pick date]
    B --> C[Select time slot]
    C --> D[Confirm booking]
    D --> E[Owner notification]
    E --> F[Reminders 24h / 2h]
```

## Architecture

```mermaid
flowchart TB
    U[Telegram User] --> B[Telegram Bot]
    U --> W[Mini App UI]
    B --> API[Booking API]
    W --> API
    API --> DB[(Database)]
    API --> SCH[Scheduler]
    SCH --> B
    API --> GCAL[Google Calendar<br/>optional]
```

---

## Packages

You get a **working bot for your business** — not a raw code dump.

| Package | What's included | Timeline* |
|---------|-----------------|-----------|
| **Launch** | Deploy, webhook, branding, pricing setup | 2–4 days |
| **Full Setup** | Launch + niche customization + payments + calendar | 4–10 days |
| **Custom** | Multi-service, integrations, advanced flows | On request |

\* Depends on scope and integrations.

> Pricing is custom based on niche, language, integrations, and support.

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Backend | FastAPI, Aiogram |
| Database | PostgreSQL / SQLite |
| Scheduler | APScheduler |
| Frontend | Telegram WebApp (vanilla JS) |
| Integrations | Google Calendar (optional) |
| Hosting | Render and similar platforms |

---

## FAQ

<details>
<summary><b>Do I need a separate website?</b></summary>
<br>
No. Clients book directly inside Telegram via the Mini App.
</details>

<details>
<summary><b>Can it match my brand and niche?</b></summary>
<br>
Yes. Each deployment gets custom colors, copy, services, and booking rules — as shown in the niche examples above.
</details>

<details>
<summary><b>Can payments be connected?</b></summary>
<br>
Yes, within the Full Setup or Custom package scope.
</details>

<details>
<summary><b>Does it work without Google Calendar?</b></summary>
<br>
Yes. Calendar sync is fully optional.
</details>

<details>
<summary><b>Is this repo the full source code?</b></summary>
<br>
No. This is a public product showcase. The live bot is delivered and deployed as a managed service per agreement.
</details>

---

## Contact

Want a demo or a quote for your business? Send:

- your niche (trainer, barber, tutor, etc.)
- interface language
- currency and pricing model
- target launch date

| | |
|---|---|
| **Telegram** | `@your_username` |
| **Email** | `you@example.com` |

<div align="center">

<br>

**Book clients inside Telegram — while your competitors are still scheduling in DMs.**

<br>

[![Message on Telegram](https://img.shields.io/badge/Message_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/your_username)

</div>

---

<div align="center">
<sub>Public product showcase · Commercial use by agreement · <a href="LICENSE_COMMERCIAL.md">Terms</a></sub>
</div>
