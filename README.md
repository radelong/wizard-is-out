# The Wizard Is Out

A four-act parser text adventure about the worst house-sitting weekend in wizarding history.

You agreed to watch Mordrath the Unyielding's house while he's at a conference. Then you used his summoning circle as a coaster.

| Act | Day | Problem |
|-----|-----|---------|
| I. The Coaster Incident | Friday night | Close the portal before Accounts Receivable arrives at midnight |
| II. The Intern | Saturday | Catch the imp intern redrawing the circle before sundown |
| III. Mother | Sunday | Survive a visit from Gerald's mother without raising suspicion |
| IV. Small Claims | Monday | Win your case in the Infernal Small Claims Court |

## Play

Open `index.html` in any modern browser. No install, no build step, no server. Everything is in one file; the only network request is for Google Fonts, and the game falls back to system fonts without it.

## Commands

`LOOK`, `EXAMINE thing`, `TAKE` / `DROP`, `INVENTORY`, `N S E W`, `OPEN` / `CLOSE`, `USE thing ON thing`, `PUT thing IN thing`, `GIVE thing TO someone`, `TALK TO someone`, `SAY something`, `WAIT`, `MAP`, `HINT`, `SCORE`.

## Saving

`SAVE` and `RESTORE` use the browser's localStorage (key `wizard-is-out-save-v2`). Saves stay in that one browser on that one machine. `RETRY` replays the current act from its start; `RESTART` goes back to Friday.

## Scoring

100 points per act, 400 total.
