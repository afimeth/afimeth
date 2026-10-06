# Iceberg — afimeth design system

Extracted from two existing surfaces and merged into one token set:

| Source | What it contributed |
|---|---|
| `assets/profile-evidence-iceberg.svg` (this repo) | Brand layer: near-black gradient surface, single amber signal `#f1c232` → `#7a651b`, cream ink ramp, uppercase tracked labels, the iceberg / waterline motif |
| `afimeth/personal-alexandria-transcripts` → `packages/corpus-atlas/index.html`, `scripts/corpus_atlas.py` | Product layer: control styling (8px radii, 1px lines), cyan focus `#67e8f9`, amber route `#ffcb73`, and the 9-color evidence-class palette |

## Files
- `tokens.css`: CSS custom properties. Dark is canonical. A derived light theme ("paper") applies via `prefers-color-scheme` or `data-theme="light"`.
- `tokens.json`: the same tokens for non-CSS consumers.
- `index.html`: specimen page with palette, type scale, controls, receipt card and evidence-chain pattern.

## Rules
1. **One accent.** Signal amber marks the single most important thing on a surface: the runnable tip, a primary action, a claim. Don't use it decoratively.
2. **Color encodes evidence class.** The `--ev-*` palette is reserved for data (graph nodes, badges, receipts). It is not for UI chrome.
3. **Limits are first-class.** Every receipt or claim component has a slot for a dashed `limit` block.
4. **Provenance is mono.** Hashes, paths and line refs use `--font-mono` in `--ink-faint`.
5. **Labels are uppercase** at 10–12px with `--track-label` (0.14em).

## Decisions made during extraction
- The sources use about a dozen slightly different greys (`#9b9b94`, `#aaa79f`, `#bdb9ae`, `#99acc9`…). These were collapsed into a four-step ink ramp.
- The Atlas's navy base (`#070d1d`) was dropped in favor of the banner's neutral black, so that brand and product share one surface.
- The light theme is new; neither source has one. On light backgrounds, text-colored signal switches to `--signal-deep`.
