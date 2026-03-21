# 💪 Workout Tracker

A production-ready fitness tracking app built as a single-file Progressive Web App
and packaged as an Android APK. No frameworks. No build step. Just HTML, CSS, and JS.

🌐 **Live App:** [your-app-here](https://workout-tracker-app-lemon.vercel.app/)

---

## Features

- 🏋️ Log weighted, bodyweight, cardio, and duration exercises
- 📊 Live Epley 1RM estimates and cardio pace calculator
- 🏆 Personal record tracking across 100+ exercises
- 📅 Calendar view with workout history
- 📈 Wilks & DOTS strength score calculators
- ☁️ Cloud sync across all devices (Supabase)
- 📤 JSON export / import with duplicate detection
- 📱 Android APK available for direct installation

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Vanilla HTML5 / CSS3 / JavaScript (ES2022+) |
| Auth & Database | Supabase (PostgreSQL + Auth + RLS) |
| Hosting | Vercel |
| Mobile | Android APK — WebView wrapper |

## Architecture

The entire app is a single `index.html` file. Screen navigation is handled
by swapping innerHTML in JS — no router, no bundler, no framework.
All data is user-scoped and secured via Supabase Row Level Security (RLS).

## Getting Started

1. Clone the repo
2. Open `index.html` in a browser — or deploy to any static host
3. Create an account and start logging


## Supabase Tables

- `sets` — workout sets with weight, reps, date, cardio fields
- `exercises` — user exercise library with body part and equipment
- `profile` — name, age, bodyweight, height, gender, avatar



workout-tracker  fitness  pwa  supabase  vercel  vanilla-js  android  
progressive-web-app  html  css  javascript  mobile  no-framework
