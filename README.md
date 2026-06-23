# Custom Porcelain Doll — Print-on-Demand Store

Print-on-demand for **custom look-alike porcelain dolls**. A customer uploads a
few photos, picks options (size, hair, outfit, stand, packaging), pays, and a
manufacturer produces and ships the doll direct to the customer. The business is
designed to be **simple and mostly hands-off**: the site captures the order +
photos and forwards everything to a maker who handles production + fulfillment.

## Status

Greenfield. We are at **M1 (Foundation)**. See the full plan and milestones in
[`docs/PLAN.md`](docs/PLAN.md).

## Stack (decided)

- **Storefront:** Shopify (payments, checkout, tax, order management built in).
- **Custom code (this repo):** a small Shopify app (Remix + Shopify CLI) + a
  theme app extension for photo upload, and an `orders/paid` webhook that
  auto-forwards each paid order + photos to the manufacturer.
- **Manufacturer:** not yet selected — sourcing is the gating item. See
  [`docs/business/manufacturer-sourcing.md`](docs/business/manufacturer-sourcing.md).

## Repo layout

```
docs/
  PLAN.md                         # master plan + milestones
  business/
    manufacturer-sourcing.md      # shortlist, scorecard, outreach email, sample checklist
    pricing-worksheet.md          # unit economics / margin model
    policies.md                   # photo-rights/likeness ToS, breakage & refund policy
  build/
    shopify-setup-runbook.md      # M1 store setup steps (needs Shopify admin access)
    architecture.md               # Shopify app + webhook design (M2/M3)
app/                              # (added in M2) Shopify Remix app
extensions/                       # (added in M2) theme app extension (photo uploader)
```

## What's next (needs the user)

1. **Brand name + domain** — needed for Shopify + sending email.
2. **Pick the material direction** — true porcelain (pricier, likely MOQ>1,
   hand-sculpted) vs vinyl/silicone "porcelain-look" (photo→doll at MOQ 1 is
   readily available). See sourcing doc.
3. **Budget for a sample order** to validate quality before launch.
