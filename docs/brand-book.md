# [app name] brand book

A friendly stretch coach, 7 minutes a day. Calm mint, indigo you tap, red when you win.
The visual version is [screens/0-01-Brand-BrandBook.html](../screens/0-01-Brand-BrandBook.html).

## Colours
| Name | Hex | Use |
|---|---|---|
| Indigo | #2B2D6E | All text, every button you tap, progress bars, the hoodie |
| Tomato red | #E5484D | Progress, streaks, ticks, the dot inside main buttons |
| Mint | #E6F5EF | Every screen background |
| White | #FFFFFF | Cards, answer rows, small round buttons |
| Mint deep | #CDEDE1 | Circle behind the coach, hero areas |
| Mint light | #F1F7F4 | Stat tiles, icon circles inside rows |
| Track | #CFE6DC | Empty part of progress bars |
| Grey | #4F5E59 | Secondary text only |
| Border | #D5DDD9 | Empty radio buttons, unselected cards |
| Red dark | #C2343A | Shading on red (headband, shoes) |
| Indigo deep | #1E2057 | Shading on the hoodie |
| Sparkle | #F5B83D | Tiny celebration sparkles only |

Rules: indigo means "tap this", red means "you made progress". No other accents, gradients or dark screens. Red is never a big button, only a small dot, tick or number.

## Type
- Inter for everything on screen. Timer 108/800, screen title 28/800, exercise name 24/800, answers and buttons 17 to 18/700 to 800, small text 15/600 grey.
- Fredoka 700 only for the coach's speech bubbles and streak numbers.

## Buttons and parts
- Main button: indigo pill, 56 tall, red arrow dot on the right. One per screen.
- Starting a stretch: red play dot on the left ("Start · 7 min").
- Round buttons: 44 (close, back), 56 (skip), 84 indigo (play/pause).
- Answer rows: white; the picked one gets an indigo border and a red tick.
- Progress bar: indigo done, track for what's left.
- Week dots: red done, red ring today, grey to come.
- Sign in with Apple keeps Apple's own button style.

## The coach
Same look always: dark brown hair, red headband tilted back, indigo hoodie, red shoes. Sits on a mint deep circle. Waving to greet, standing on Home, cheering for wins, stretching to demo moves. Talks in short, friendly first-person lines. Drawings are in [assets/coach](../assets/coach).

## How we talk
- Say "stretch", never "workout".
- Say "days in a row"; "weeks in a row" only after a daily streak breaks.
- Friendly coach, not a clinic: "feel less stiff", never "fix your back".
- No medical questions in onboarding; safety is a short statement.
- Use their name, short sentences, one idea per screen.
- Never invent numbers, reviews or press quotes.

## Shape and spacing
Screen 390 × 844, 20 side padding. Corners: buttons 28 (fully round), cards 24 to 30, answer rows 20, tiles 16 to 18. Soft shadows only, no card borders. Gaps 10 between rows, 14 to 20 between blocks. Icons 2.2 stroke, rounded, in a 40 light-mint circle.

## Screen names
Format: `number · area · state`, e.g. **1.03 Onboarding · Goal** (file `1-03-Onboarding-Goal`).
0 Brand · 1 Onboarding (ends with the paywall) · 2 Home · 3 Stretch · 4 Settings.
New ideas get a letter (1.03a, 1.03b); the winner drops the letter.
