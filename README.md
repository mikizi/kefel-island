# אי הכפל (Kefel Island)

A gamified multiplication-tables learning game for kids ages 8-10, built as a single self-contained HTML file (Hebrew, RTL).

## Concept

Kids explore a pirate-adventure island where each region teaches a group of multiplication tables, following the research-backed learning order (2/5/10 → 3/4 → 6/9 → 7/8 → mixed mastery):

1. 🏖️ חוף הפתיחה — tables 2, 5, 10
2. 🌴 יער הבמבוק — tables 3, 4
3. ⛰️ הרי הערפל — tables 6, 9
4. 🌋 געש האש — tables 7, 8
5. 🏛️ מקדש האוצר — mixed boss review (all tables)

## Features

- **Visual array demos** before drilling each region, reinforcing multiplication as repeated addition/skip-counting.
- **Adaptive practice** using a lightweight Leitner-style spaced-repetition box per fact — weaker facts resurface more often, across sessions.
- **Arcade "flash challenge" mode** for fast-paced timed review across all unlocked regions.
- **A mastery grid** (all facts 2×2–9×10) for free-choice single-fact drilling.
- **Gamification**: XP levels, gold coins, unlockable companion characters, achievement badges, streaks, and confetti — all persisted locally via `localStorage`.
- Fully self-contained: no build step, no external dependencies besides Google Fonts.

## Running it

Just open `index.html` in a browser, or serve the folder with any static file server.
