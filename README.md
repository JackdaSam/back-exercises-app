# Back exercises app: designs

Screen designs for a simple back-stretching app: a friendly coach, 7 minutes a day, a 3-day free trial.
These are design files (look and wording), not the working app yet.

**Start here:** open [`index.html`](index.html) to see every screen in order.

## What's in here

| Folder | What it is |
|---|---|
| `index.html` | One page showing all screens, in flow order |
| `screens/` | Each screen as its own web page (390 × 844, phone size). Open in any browser |
| `screenshots/` | A picture of each screen (PNG) |
| `assets/coach/` | The coach drawings: standing, waving, cheering, glute bridge (SVG) |
| `docs/brand-book.md` | Colours, fonts, buttons, wording rules, naming |

## The flow

0. **Brand**: brand book, coach character
1. **Onboarding**: welcome, name, goal, what gets in the way, when to stretch, reminder, where you heard about us, safety note, plan ready, sign up, paywall
2. **Home**: streak going, new user, welcome back, done for today, weeks in a row, trial ended
3. **Stretch**: exercise, next up, exercise info, paused, end check, done, milestone
4. **Settings**: main (reminders, account, subscription), safety info

## Naming

`number · area · state`, e.g. **1.03 Onboarding · Goal** → file `1-03-Onboarding-Goal`.

## Placeholders

- `[app name]` and `[PRICE]` are not decided yet.
- Exercise demos currently all show the Glute Bridge.

## Product decisions so far

- It's a **stretch**, never a "workout".
- Streaks count **days in a row**; "weeks in a row" only shows after a daily streak breaks. Half-finished stretches don't count.
- **3-day free trial**; sign-up happens during onboarding, before the paywall.
- Onboarding questions stay general, not medical. Safety is a short statement.
- Settings has account and subscription sections (sign out, delete account, restore purchases).
