# Policies (draft — review with a professional before publishing)

These protect the business and set customer expectations. They are **drafts**;
have a lawyer review before going live, especially likeness/minors clauses.

## 1. Photo rights & likeness consent (REQUIRED before taking orders)

At checkout/upload, the customer must affirmatively agree:

- They **own or have permission** to use the uploaded photos.
- They **consent to a likeness** of the depicted person being made into a doll.
- If the depicted person is **someone else**, they confirm they have that
  person's consent.
- **Minors:** [DECISION NEEDED] Either (a) decline dolls of minors, or (b)
  require the buyer to confirm they are the **parent/legal guardian** of the
  depicted child. Recommend a clear, explicit checkbox and the right to refuse
  any order. This is a deliberate policy choice — flag in `docs/PLAN.md` open
  items.
- We may **refuse or cancel + refund** any order at our discretion (e.g.
  suspected non-consensual likeness, public figures, prohibited content).
- We do not use customer photos for marketing **without separate opt-in**, and
  we delete source photos [after X days / on request].

Implementation: a required consent checkbox in the photo-upload extension (M2),
with the agreed text version stored on the order as a line-item property.

## 2. Breakage, damage & refunds

Porcelain is fragile — a clear policy reduces disputes:

- **Arrives damaged:** customer reports within [7] days with photos → free
  remake or full refund. Require the maker to **insure/replace** damaged
  shipments (vet in sourcing).
- **Custom = limited returns:** because each doll is made to order, we do not
  accept "change of mind" returns once production starts; we **do** stand behind
  defects and likeness that clearly misses the provided photos.
- **Production timeline:** state lead time honestly ([X–Y] weeks) since custom
  porcelain is slow.

## 3. Content / acceptable use

- No likenesses intended to harass, defame, or impersonate.
- No public figures/celebrities without rights.
- We may decline anything unlawful or against these terms.

## 4. Privacy

- What we collect (photos, contact, shipping), why (to fulfill the order), who
  we share with (the manufacturer, for production/shipping), and retention.
- Honor deletion requests; comply with applicable privacy law for our markets.

## Where these live on the site

- Shopify policy pages (Refund, Privacy, Terms) + a dedicated **Custom Order
  Terms / Photo Consent** page linked from the upload step and checkbox.
