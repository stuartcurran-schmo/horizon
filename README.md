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

## Using the board

Everything happens on the board itself:

- **Add**: select **+ Add card** in any cell to add a topic (an idea, opportunity or question) or a source (a fact with a reference). Press Enter to keep adding.
- **Cluster**: drag a card onto another card to stack them into a named theme, or onto an existing stack to add it. Select a stack to rename it or drag cards back out.
- **Connect**: drag the orange handle on a stack (it appears on hover) to another stack to start a thread. Drag from the last stack in a thread to extend it.
- **Move**: drag a card or stack to empty space in another cell.

A separate **Story** view shows the written narrative, insights, and a check for structural gaps.

Board settings let you rename the horizons and layers. Every action can be undone.

## Running it

It's a single self-contained `index.html` with no build step. Open it in a browser, or serve it with GitHub Pages.

Run outside claude.ai, boards are saved in the browser's local storage. Use **More → Export data** to keep a JSON copy, and **Import** to load it again.

## Claude features

Auto-cluster, auto-connect, name suggestions and the written narrative use Claude. When the page runs as a Claude artifact they work with no setup. Anywhere else, open **Board settings** and add your own Anthropic API key (get one from the [Anthropic Console](https://console.anthropic.com/settings/keys)). The key is stored only in that browser and sent only to Anthropic, and usage is billed to your Anthropic account. Without a key, "Draft from structure" still writes a basic narrative from the board.
