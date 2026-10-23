# Big Walk data reference

An independent, public data companion for the co-op game **Big Walk**. It packages 37 puzzle records and 12 achievement milestones in JSON, with a readable static page for players and researchers.

- Live reference: https://szj2ys.github.io/thebigwalk-data/
- Maintained puzzle walkthroughs: https://thebigwalk.world/en/puzzles
- Coordinate finder and map: https://thebigwalk.world/en/map
- Achievement funnel: https://thebigwalk.world/en/achievements

## Data

- `docs/data/puzzles.json`: puzzle IDs, names, tower, player-count label, solve window, difficulty, depth, optional coordinates, and reward type.
- `docs/data/achievements.json`: Steam API names, official achievement names, milestones, global completion percentages, tower, and optional walkthrough ID.
- `docs/data/summary.json`: counts, tower distribution, and the achievement collection date.

The solve windows are documented guide estimates, not measured completion times. Achievement percentages are a Valve snapshot collected on 2026-09-30 and will change.

## Provenance and scope

The factual fields are exported from the maintained The Big Walk guide dataset on 2026-10-24. Walkthrough prose, illustrations, screenshots, and artwork are deliberately omitted. This project is not affiliated with the game's developers or publishers.

Corrections are welcome in the issue tracker.
