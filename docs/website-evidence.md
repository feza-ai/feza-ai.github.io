# Website evidence correction

Updated 2026-10-09. Owner: Codex coordinator. Scope: replace invalid historical performance claims with documented existing capabilities; preserve the page design and acquisition intent.

## Sources and decisions

- Wolf README, SHA-256 `1d4d9ad89f87b04307c17874df4152484a1f33a58b23ce5a0f10dbc755ae7515`: reusable Go services, training/backtest components and SwiftUI tooling exist. No sustainable edge is established. COIN research and controlled Alpaca paper trading are the roadmap, with activation gates; live trading is not authorized.
- Wolf audit receipt, SHA-256 `aa2ff5f932fd88c075adabb48d0039bfd55cdf5023a0fa77414864b3a8d2bc8b`: evaluation and recovery gaps despite component test success.
- The adjacent current Wolf checkout is the editorial source. The pre-existing DGX Wolf checkout is an older revision and was left untouched. Source documents and website Git bundle were transferred with matching SHA-256 hashes; no credentials or environment files were transferred.
- Primary replacement: Go / Research Stack. Related stale validation figures replaced with existing components and explicit paper-activation status. No new performance percentage is asserted; withdrawn metrics and their history are omitted from public copy.
- Existing future vision and unrelated Zerfoo technical claims are outside this correction's validation scope. This receipt is not evidence for those claims.

## Execution ownership

Coding and verification run in an isolated task checkout on DGX storage. Original Mac checkout is preserved. Codex coordinator owns implementation and delivery; independent reviewer owns exact-head review. No active Git operation or uncommitted source was present at transfer.
