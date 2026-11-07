# Horizon Blueprint

An interactive board for the Horizon Blueprint planning method, which places today's work alongside future ambitions so you can see where the most impact lies. The method is written up at [schmo.uk](https://schmo.uk/blog/introducing-the-horizon-blueprint).

## The board

Three columns of horizons, read pragmatically as planning cycles:

- **H1**: the current plan cycle
- **H2**: the next plan cycle
- **H3**: beyond the plan

Three rows, which form a simplified business stack:

- Customer / market
- People / operations
- Partners / technology

## Modes

1. **Collect**: add topics (ideas, opportunities, questions) and sources (facts with a reference) directly into cells.
2. **Cluster**: drag one card onto another to stack them into a named theme, or drag a card onto an existing stack to add it.
3. **Connect**: drag from one stack's handle to another stack to start a thread across horizons and layers.
4. **Story**: the finished board with a written narrative, insights, and a check for structural gaps.

Board settings let you rename the horizons and layers. Every action can be undone.

## Running it

It's a single self-contained `index.html` with no build step. Open it in a browser, or serve it with GitHub Pages.

Run outside claude.ai, boards are saved in the browser's local storage. Use **More → Export data** to keep a JSON copy, and **Import** to load it again. The Claude-assisted features (auto-cluster, auto-connect, name suggestions and the written narrative) are only available when the page runs as a Claude artifact. "Draft from structure" works everywhere.
