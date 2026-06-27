# Football Tournament Management Program

A football tournament program for creating and managing a tournament from setup to final results.

The easiest version to run is the standalone GUI:

```text
FootballTournamentManager.html
```

Double-click that file and it will open in your web browser. It does not need Python or installation.

## Features

- Graphical browser interface
- Home page with a short program overview
- Mobile-friendly navigation and responsive match screens
- Light mode and dark mode
- Tournament name entry
- Round Robin, Double Round Robin, Knockout, Double Elimination, and Two-Legged Knockout formats
- Team, player, captain, and goalkeeper setup
- Captain display using `(C)`
- Goalkeeper display using `[GK]`
- Optional player mastery tiers: E, D, C, B, A, S, S+
- Optional player positions, such as ST, CM, FW, CB, LB, and RW
- Randomize teams from a full player list
- Level Randomize to balance teams by player mastery tier
- Optional captain and goalkeeper selection after randomized teams are created
- Beginner-friendly format explanation panel
- Hover tooltips for optional features
- Random match generation
- Custom win, draw, and loss point values, including negative numbers
- Round Robin and Double Round Robin ties are broken by total team goals
- Match timer with hours, minutes, seconds, Start, Pause, Resume, and Reset
- Mobile card layout for player statistics entry
- Tie-break methods for winner-required matches:
  - Penalties
  - Extra Time
  - Golden Goal
- Bracket display for Knockout, Double Elimination, and Two-Legged Knockout when there are at least 4 teams
- Even starting team validation for Knockout, Double Elimination, and Two-Legged Knockout
- Tournament Cup title in final results
- Match-by-match player statistics:
  - Goals
  - Assists
  - Interceptions
  - Goalkeeper saves
- Final results with:
  - Tournament winner
  - Winning team players
  - Top scorer
  - Top assister
  - Best keeper
  - Best Defender
  - POTM based on goals + assists + interceptions
- Export and import tournament data as JSON

## Run the GUI

Open this file:

```text
FootballTournamentManager.html
```

## Run the Python Console Version

Use Python 3.10 or newer:

```bash
python main.py
```

The GUI version is recommended if you want to run the program on another computer without installing Python.
