<p align="center">
  <img src="public/favicon.svg" alt="GPA Forecaster" width="64" />
</p>

<h1 align="center">GPA Forecaster</h1>

<p align="center">
  <strong>Plan your classes. Predict your GPA. Reach your dream school.</strong>
</p>

<p align="center">
  <a href="https://gpaforecaster.lovable.app">gpaforecaster.lovable.app</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-5.8-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-v4-06B6D4?logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-PostgreSQL-3ECF8E?logo=supabase&logoColor=white" />
</p>

---

## What is GPA Forecaster?

**GPA Forecaster** is a free, modern student dashboard built to help you stay on top of your academic journey. Add every class you have taken, see your GPA evolve in real time, and use smart forecasting to figure out exactly what grades you need to hit the GPA required by your target school.

Whether you are a community college student planning a transfer or just want a clearer picture of your academic standing, GPA Forecaster gives you the tools to plan with confidence.

---

## Features

| Feature | What it does |
|-------- | ------------ |
| Class History | Add classes with grades, credits, season, year, and custom tags. Edit or remove anytime. |
| Auto GPA | Cumulative and term-by-term GPA calculated instantly as you type. |
| Forecasting | Two modes: general prediction or customized term-by-term planning. |
| Target Schools | Save institutions with goal GPAs. Visual goal lines show how close you are. |
| Reports | Generate clean, print-friendly academic reports with charts and stats. |
| Data Export | Download a JSON backup of your full history and profile. |
| Cloud Sync | Sign in with Google and pick up where you left off on any device. |
| Dark Mode | Full dark theme support for late-night study sessions. |
| Mobile Ready | Responsive design that works on desktop, tablet, and phone. |

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Framework | [TanStack Start](https://tanstack.com/start) — React 19, SSR/SSG, file-based routing |
| Styling | [Tailwind CSS](https://tailwindcss.com) v4 |
| Charts | [Recharts](https://recharts.org) |
| Auth & Database | [Supabase](https://supabase.com) — PostgreSQL + Row Level Security |
| Build Tool | [Vite](https://vitejs.dev) |
| Language | TypeScript |

---

## Getting Started

### Prerequisites

- [Bun](https://bun.sh) (or Node.js 20+)
- A Supabase project with the following tables:
  - `profiles` — user onboarding data (name, school, major, institutions, etc.)
  - `user_app_data` — synced localStorage keys for classes, tags, and settings
  - `feedback` — user feedback submissions


