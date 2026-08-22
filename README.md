# aos-player — Player Content

Player-facing content for the [Age of Sail](https://github.com/age-of-sail) RoleMaster campaign.

This repository contains material that is public knowledge to the players — documents the GM has
released in-game or that players are expected to have access to.

## Contents

Anything under [`Published/`](./Published/) is meant to end up in the generated site; everything
else in the repo is not. `aos-site build`/`deploy` reads each subfolder of `Published/` and copies
it into the generated site as a top-level section — a peer of `Sessions`, not nested under a
"Published" folder.

Files under `Published/` are copied verbatim, with no stripping. Keep them plain player handouts:
a bare `# Title` plus content is fine, but no `README.md`, and no repo-browsing nav bar
(`[^ Up](...) | [X Home](...)`) or `## Table of Contents` — those render as broken, dead-linked
pages on the live site, which builds its own navigation. That repo-browsing convention is still
correct for unpublished folders (e.g. [`Miscellaneous/`](./Miscellaneous/README.md)) and elsewhere
in the org.

| File / Directory | Description |
|---|---|
| [`Published/Interludes/`](./Published/Interludes/) | Narrative pieces distributed to players between sessions |
| [`Published/TheMedallion/`](./Published/TheMedallion/) | Documents relating to the ship *The Medallion* — articles of agreement, crew list, watch assignment, final accounting |
| [`Published/TheKingship/`](./Published/TheKingship/) | Documents relating to the ship *The Kingship* |
| [`Published/Miscellaneous/`](./Published/Miscellaneous/) | Assorted player-facing material — Christmas note, Mason's wife's letter |
| [`Miscellaneous/`](./Miscellaneous/README.md) | Assorted material — draft/example ship articles, GM-only letter with notes. Not published. |
