# NARA Calling Hub · super AI

Interactive design demo of the NARA Calling Hub: a live call-center workspace for admins, team leads and agents, with real-time coaching from super AI.

Everything is static HTML. Open `index.html`, or the GitHub Pages link once Pages is on.

## Start here

| Open | What it is |
|---|---|
| `index.html` | Landing page, the start of the demo |
| `presentation.html` | Presentation for a PC or big screen (every screen runs live inside the slides) |
| `presentation-mobile.html` | The same presentation for a phone |

## Demo path

Landing page → **Login** → choose a role → **Access platform**

- **Admin**: every screen, every team.
- **Team lead**: every screen except Billing. Monitoring shows only their team.
- **Agent**: only *My day* and the live call screen, plus the dialer. Any other screen sends them back to *My day*.

## Screens

| File | Screen | Who |
|---|---|---|
| `dashboard.html` | Dashboard with the super AI brief | Admin, team lead |
| `team-board.html` | Team board: every agent's numbers, listen / whisper / barge in | Admin, team lead |
| `monitoring.html` | Monitoring: live status of all agents, long-idle alerts | Admin, team lead |
| `command-view.html` | Command view: 3D call-center floor | Admin, team lead |
| `live-calls.html` | Live calls | Admin, team lead |
| `active-call.html` | One call in detail | Admin, team lead |
| `analytics.html`, `history.html`, `agents.html`, `teams.html`, `targets.html`, `leads.html` | The rest of the menu | Admin, team lead |
| `billing.html` | Billing | Admin |
| `agent-home.html` | *My day*: the agent's home | Agent |
| `agent-focus.html` | The agent's live call screen | Agent |
| `login.html` | Sign-in with role choice | Everyone |

## Things to try

- **▶ Agent call demo** (Dashboard top bar, or *Start calling* on *My day*): the dialer calls a client and connects, and the agent lands on their live call screen.
- **DIALER** tab on the right edge: keypad, statuses (break, lunch, restroom, coaching, meeting, training…), mute, hold, transfer, ask coach, wrap-up.
- **☀ / ☾** button: switches between the dark and the light (NARA colours) version.

## Notes

- Client phone numbers are never shown; agents see client references only (GDPR).
- Sign-in accepts anything: this is a design demo, with no real accounts and no data leaving the page.
- Numbers come from the team's screenshots; Leads, History and Billing prices are marked as sample data.
