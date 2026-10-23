# Tinderbox Works plugin for Claude Code

The `tinderbox-works` marketplace with one plugin, `tinderbox`. It teaches Claude Code to work on the AI Agent tasks Tinderbox Works prepares for a game, through the `tinderbox` CLI.

In Claude Code, type `/plugin`, choose **Add › Marketplace** and paste `Rora/tinderbox-plugin`. Then, on the **Discover** tab, open the filter next to Search, pick the source **tinderbox-works** and install **Tinderbox**.

From a terminal instead:

```text
claude plugin marketplace add Rora/tinderbox-plugin
claude plugin install tinderbox@tinderbox-works
```

Then, in the game's repository: `tinderbox login`, `tinderbox link <project>`, and say **"Work on Tinderbox Works tasks"**.
