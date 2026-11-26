# XingChen-AGI Pricing

Public price card for XingChen-AGI models.

- Served via GitHub Pages: https://xingchen-agi.github.io/pricing/
- Covers Xing4.1-Preview: USD list prices plus the limited-time offer through 2026-12-20 (20% of list).
- `index.html` is the live page; `index.full.html` is kept as an identical copy for editing/rollback.
- Source of truth for the figures used in upstream catalog PRs (models.dev, OpenClaw, Kilo) and in the pricing fields of provider plugins.
- Official product page (account, free trial, billing): https://www.teleai.com.cn/product/Xing4-1-Preview

## Current prices (USD per 1M tokens)

| Xing4.1-Preview | List price | Limited-time offer (20% of list, through 2026-12-20) |
| --- | --- | --- |
| Input (cache miss) | 0.225 | 0.045 |
| Input (cache hit) | 0.01125 | 0.00225 |
| Output | 0.90 | 0.18 |

Cache-hit price is 5% of the corresponding input price. No peak/off-peak tiers apply.
