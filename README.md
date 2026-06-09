# Decor Set Store: A Case for Sellable Level-Ups

A data-grounded case for letting Top War players reach a decoration set's maximum level
through the Decor Set Store, paid in small weekly token installments, instead of only through
expensive time-limited launch packs. A level-up is worth +2 march size; almost nobody pays a
$350 to $875 lump sum for that, but a roughly $5-a-week habit toward a visible goal is one a
spender pays gladly, week after week. Getting the older backlog into the store on the studio's
existing cadence is the access step that makes the grind possible; the newest sets stay
premium and the monthly pop-up packs stay intact. Only Metal Music Fans and Sweet Haven can
reach level 3; every other set caps at level 2.

**Live: https://texnottexas.github.io/decor-set-store-case/**

## Seven views of one case

The landing page is a thin shell with a toggle at the top. The same argument and the same
verified numbers are presented seven ways, four general framings and three tuned to a
specific reader:

1. **The Brief** (`brief.html`): a warm, dark editorial strategy brief with two interactive models.
2. **The Data Room** (`terminal.html`): a quant trading-desk dashboard with a live model, a sensitivity table, and a cannibalization stress test.
3. **The Story** (`story.html`): a light scrollytelling piece following one player's year, with big infographics and a small interactive lab.
4. **The Memo** (`memo.html`): a one-page executive decision memo, bottom line up front, built to print cleanly to PDF.
5. **The Scorecard** (`pm.html`): for the product manager who owns the cadence, framed as KPIs, an A/B design, and a rollout plan.
6. **The Ledger** (`exec.html`): for the executive above them, framed as a statement of forgone revenue with a P&L and an opportunity-cost chart.
7. **The Spender** (`whale.html`): the voice of the paying players, who are asking to be allowed to spend.

Switch views with the tabs (or number keys 1 to 7). Deep-link a view with `?v=brief`,
`?v=terminal`, `?v=story`, `?v=memo`, `?v=pm`, `?v=exec`, or `?v=whale`.

## English and Simplified Chinese

Every view exists in English and in native Simplified Chinese. Use the EN / 中文 toggle in
the top bar to switch languages while keeping the current view. The Chinese pages are written
to read naturally for a native speaker, not machine-translated; money figures are kept in `$`.
The companion file for each view is the same name with a `.zh` suffix (for example
`exec.zh.html`), and a view can be deep-linked in a language with `&lang=zh` or `&lang=en`.

## Notes on the numbers

Set names, prices, release dates, and the token economy are read from the live game client.
The revenue figures are an illustrative model, and its assumptions (player counts, tier mix,
release cadence, give-up rate) are exposed as on-page controls so they can be adjusted and
challenged. All seven views share one model, so the figures agree across them. All revenue
shown is scoped to token-store revenue from the 10 older sets only, not total game revenue.

Self-contained HTML files. No build step, no dependencies, no tracking.

By a Server 2864 player.
