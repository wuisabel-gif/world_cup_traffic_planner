# 🚇 World Cup Traffic Planner

### Eight matches. 70,000 fans a game. One very tired freeway.

This is the tool that gets you to SoFi Stadium without losing your mind — or, if you're just trying to make it to work, gets you *around* the chaos. LA's hosting the 2026 World Cup at SoFi, and the roads around Inglewood are about to have a month they'll never forget. Plan accordingly.

**▶ Try it live →** https://wuisabel-gif.github.io/world_cup_traffic_planner/

---

## So what does it actually do?

You tell it two things — where you are and when you're moving — and it tells you the smart play. There are two ways to use it:

**🎟️ Going to the match.** Pick your starting point, your match, and when you'd leave. You get a real, step-by-step transit route — *board the E Line here, swap to the K Line there, hop the shuttle to the gate* — plus a read on whether you're beating the rush or walking into it. Want to compare leaving at 9 vs. 11? Drop in two times and see them head to head.

**🚗 Getting around it.** Not going to the game? Smart. Tell it your neighborhood and a match date, and it'll tell you straight up: are you in the blast radius, when's the window to avoid, and which freeways to dodge. Because nobody should accidentally end up on the 405 next to the stadium at kickoff.

## The good stuff

- 🗺️ **A live map** with every $1.75 express-bus hub, the Metro K Line, and SoFi — your route drawn right on it.
- 🚉 **Real station-to-station directions.** No hand-waving. Actual lines, actual transfer points.
- 🎨 **Metro's real line colors** on every step, so it reads like a transit map should.
- ⏰ **A "next disruption" banner** that always knows which match is coming up and counts you down to it.
- 🚦 **Drive-time guesses** — what the trip takes normally vs. what it'll cost you on match day.

## Run it yourself

It's one HTML file. No npm, no build, no backend, no excuses.

```bash
git clone https://github.com/wuisabel-gif/world_cup_traffic_planner.git
cd world_cup_traffic_planner
open index.html
```

Hosting it? GitHub Pages serves `index.html` automatically — push it, flip on Pages in your repo settings, done.

## Fair warning

This is a planning buddy, not a GPS. Distances and drive times are smart estimates, not live traffic — and Metro runs special World Cup service that can move stops around on game days. Always double-check kickoff times and service on **FIFA**, **Metro**, and **Caltrans** before you head out.

---

*Built for the city that invented the traffic jam.*

© 2026 wuisabel-gif. All rights reserved.
