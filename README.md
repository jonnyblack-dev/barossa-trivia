# Barossa Trivia Night 2026

Live trivia web app for a long weekend in the Barossa Valley (Sunday 15 November 2026).

One page, five views (hash routing):

| Link | Who | What |
|---|---|---|
| `#register` | Teams (phones) | Register a team name and both players |
| `#leaderboard` | Everyone (phones) | Live scoreboard, updated as each round is revealed |
| `#present` | TV (laptop) | Click-to-reveal quiz slides, standings reveals and confetti |
| `#admin` | Quizmaster | Enter round scores, manage teams, lock registration |
| `#answers` | Quizmaster | Answer sheet |

The quizmaster views need a PIN. Data syncs through a Firebase Realtime Database; with no database configured the page runs in a single-browser test mode.

Presenter keys: → / Space / click = next, ← = back, G = slide list, F = full screen, B = black screen.
