# CourtSide

CourtSide is a full-stack basketball statistics and prop-betting platform built for players, coaches, scorekeepers, and basketball fans.

The application combines live basketball statistics, team analytics, player leaderboards, and a sportsbook-style betting experience in one responsive platform.

## Live Application

[View CourtSide](https://www.braxtonkurth.com/#/courtside/login)

## Features

### Basketball Statistics

- Record and manage basketball game statistics
- View player and team performance dashboards
- Sort player leaderboards by major statistical categories
- Calculate advanced statistics such as field goal percentage and effective field goal percentage
- Recover stat-entry progress after a browser refresh or unexpected interruption
- Undo and redo stat-entry changes

### Prop Betting

- Generate consistent player prop lines and American odds for each game
- Build multi-leg parlays using available player props
- Calculate potential payouts in real time
- Automatically settle pending bets when a game is completed
- Grade each parlay leg against the final box score
- Void affected props and refund wagers when a selected player does not play
- Track user credits and betting records

### User Roles

CourtSide supports role-based experiences for:

- Players
- Coaches
- Scorekeepers
- Guests

Permissions and navigation are controlled through authentication metadata and the user's active session.

## Technology Stack

### Frontend

- React
- TypeScript
- Material UI

### Backend and Data

- Supabase
- PostgreSQL
- Supabase Authentication

## Technical Highlights

- Deterministic, seeded prop generation produces consistent player lines and odds for each game
- American odds are converted into decimal multipliers for multi-leg parlay payout calculations
- Automated bet settlement compares pending wagers against completed box scores
- User credit balances and win/loss records are updated atomically
- Derived statistics are calculated from the underlying box score data
- Stat-entry history supports undo and redo operations
- Local storage provides crash recovery during scorekeeping

## Project Status

CourtSide is a completed personal full-stack project and is available through the live application linked above.

## Source Code

The source code for CourtSide is maintained in a private GitHub repository.

This public repository provides project documentation, screenshots, release information, and a link to the deployed application. The production source code is not publicly distributed.

## Author

Braxton Kurth

[View My Portfolio](https://www.braxtonkurth.com/)
