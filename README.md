# aos-player — Player Content

Player-facing content for the [Age of Sail](https://github.com/age-of-sail) RoleMaster campaign.

This repository contains material that is public knowledge to the players — documents the GM has
released in-game or that players are expected to have access to.

## Contents

Anything under [`Published/`](./Published/) is meant to end up in the generated site; everything
else in the repo is not. `aos-site build`/`deploy` reads each subfolder of `Published/` and copies
it into the generated site as a top-level section — a peer of `Sessions`, not nested under a
"Published" folder.

| File / Directory | Description |
|---|---|
| [`Published/Interludes/`](./Published/Interludes/README.md) | Narrative pieces distributed to players between sessions |
| [`Published/TheMedallion/`](./Published/TheMedallion/README.md) | Documents relating to the ship *The Medallion* — articles of agreement, crew list, watch assignment, final accounting |
| [`Published/TheKingship/`](./Published/TheKingship/README.md) | Documents relating to the ship *The Kingship* |
| [`Miscellaneous/`](./Miscellaneous/README.md) | Assorted material — draft/example ship articles, Christmas note. Not published. |
