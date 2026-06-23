# Master Plan — Custom Porcelain Doll Print-on-Demand

## Overview

Customer uploads a few photos → picks options (size, hair, outfit, stand,
packaging) → pays → manufacturer produces and ships direct. Hands-off: the site
captures the order + photos and forwards everything to the maker.

**Decisions:** Shopify storefront; small custom Shopify app for photo upload +
order forwarding; manufacturer not yet chosen (gating item); AI preview deferred
to a post-purchase design proof (only pay for renders on actual buyers).

## Milestones

1. **M1 — Foundation:** Shopify store, theme, core product + customization
   variants, marketing pages. Sellable shell with manual fulfillment.
   Runbook: [`build/shopify-setup-runbook.md`](build/shopify-setup-runbook.md).
2. **M2 — Photo capture:** Shopify Remix app + theme app extension uploader;
   photos + options land on the order via line-item properties.
   Design: [`build/architecture.md`](build/architecture.md).
3. **M3 — Auto-forward:** `orders/paid` webhook → formatted email to maker
   (pluggable sender interface so a future maker API drops in cleanly).
4. **M4 — Proof loop:** post-purchase design-proof approval before production.
5. **M5 (optional):** pre-purchase AI preview experiment if conversion data
   justifies the per-render cost.

Manufacturer sourcing (Track A) runs alongside M1–M2 and **must close before we
go live** — the maker's order format finalizes M3's email template, and a sample
validates quality.

## Track A — Business (user-led, I assist)

- Source & vet manufacturers → [`business/manufacturer-sourcing.md`](business/manufacturer-sourcing.md)
- Unit economics / pricing → [`business/pricing-worksheet.md`](business/pricing-worksheet.md)
- Photo-rights/likeness ToS, breakage & refund policy → [`business/policies.md`](business/policies.md)
- Shopify account (Basic), business email, domain, payments.

## Risks / must-handle

- **Likeness & photo consent**, with extra care for dolls of minors.
- **Quality variance / breakage** — porcelain is fragile.
- **Margin** — custom porcelain is expensive; validate with a real quote +
  sample before building beyond M1.
- **Single-supplier dependency** — keep the order-forwarding sender pluggable.

## Open items to confirm

- Brand name + domain.
- Material direction: true porcelain vs vinyl/silicone "porcelain-look."
- Budget for a manufacturer sample order.
- Policy: whether to ever accept dolls of minors.
