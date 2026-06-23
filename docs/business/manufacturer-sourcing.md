# Manufacturer Sourcing (gating item)

We have **no manufacturer yet**. Everything downstream — pricing, order-export
format, launch date — depends on closing this. Goal: a maker that accepts
**photo-based custom likeness**, ships **direct-to-consumer white-label at
MOQ 1**, with acceptable cost, lead time, and a breakage/replacement policy.

## Key finding: porcelain vs "porcelain-look"

Research shows a real fork:

- **True custom porcelain from a photo at MOQ 1 is rare.** Porcelain likeness
  work is typically hand-sculpted → higher cost, longer lead time, higher
  breakage risk, and often a minimum order above 1.
- **Vinyl/silicone (and plush) custom-from-photo at MOQ 1 is readily
  available.** Several factories take ~3 photos and sculpt a ~95% likeness.

**Recommendation:** validate demand with a "porcelain-look" collectible
(vinyl/silicone with a porcelain-style finish) that supports MOQ-1 dropship and
photo→doll, OR commit to true porcelain knowing the cost/lead-time/MOQ tradeoff.
Confirm material direction before building beyond M1.

## Candidate shortlist (starting points — must be vetted/contacted)

| Maker | Material | Photo→doll | Dropship/MOQ 1 | Notes |
|---|---|---|---|---|
| Everyest (Taiwan) | Vinyl/silicone | Yes (~3 photos, ~95% likeness) | Confirm | 35+ yrs OEM/ODM; collectible-grade. Strongest photo→doll lead. |
| Papa China | Dolls incl. porcelain | Confirm | Confirm | Logo/packaging customization, bulk-oriented. |
| Beijing Baiyuesuo | Porcelain + silicone/vinyl | Confirm | Confirm | OEM/ODM; porcelain capable. |
| SONOS Product Dev | Various | Confirm | Yes (turn-key + dropship) | Turn-key production + direct dropship. |
| Alibaba / AliExpress | Various | Per-supplier | Many offer MOQ 1 | Broadest pool; quality variance — vet hard. |
| Etsy custom-doll studios | Often porcelain/handmade | Yes | Often 1-of-1 | True artisan porcelain; higher cost, slower. |

Sources:
- [Everyest custom doll](https://everyest.com/custom-your-owner-doll/)
- [Papa China dolls](https://www.papachina.com/manufacture/wholesale-dolls-doll-houses)
- [SONOS Product Development](https://www.sonosproductdevelopment.com/doll-design-development/)
- [Alibaba custom doll suppliers](https://www.alibaba.com/custom-doll-suppliers.html)
- [Alibaba dolls dropship](https://www.alibaba.com/dolls-dropship-suppliers.html)
- [Custom porcelain dolls on Etsy](https://www.etsy.com/market/custom_porcelain_dolls)

## Scorecard (rate each candidate 1–5; require a sample before committing)

| Criterion | Weight | Why it matters |
|---|---|---|
| Accepts photo-based custom likeness | High | Core product requirement |
| Sample quality / likeness accuracy | High | Drives reviews, refunds, repeat |
| MOQ = 1 (true dropship) | High | Our model can't hold inventory |
| Per-unit landed cost @ low volume | High | Determines margin/viability |
| Lead time (order → delivered) | Med | Sets customer expectations |
| Direct-to-consumer, blind/white-label | High | No maker branding in the box |
| Breakage policy / insured replacement | High | Porcelain is fragile |
| Order intake method (email/portal/API) | Med | Defines our M3 export format |
| Communication responsiveness | Med | Hands-off ops depend on it |
| Photo requirements (count/angles/res) | Med | Shapes our uploader UX |

## Outreach email template

> **Subject:** Custom photo-based dolls — dropship partner inquiry (MOQ 1)
>
> Hi [Name/Team],
>
> I run an online store selling **custom look-alike dolls made from a
> customer's photos**. I'm looking for a production partner who can:
>
> 1. Create a custom doll from **2–4 customer photos** (please share your photo
>    requirements and typical likeness accuracy).
> 2. Produce and **ship direct to my customers (dropship), MOQ 1**, with
>    **no maker branding** in the package (blind/white-label).
> 3. Material: [true porcelain / porcelain-look vinyl or silicone] — let me know
>    what you offer and the tradeoffs.
>
> Could you share: per-unit cost at low volume, shipping cost/time to the US,
> total lead time, your breakage/replacement policy, how you receive orders
> (email/portal/API), and whether I can order a **paid sample** first?
>
> Thanks,
> [Name] — [brand], [website], [email]

## Sample-order checklist (before launch)

- [ ] Send 2–4 real photos and place a **paid sample** order.
- [ ] Score likeness vs photos (front/profile), finish, paint, seams.
- [ ] Inspect packaging: protective, **no maker branding**, survives drop test.
- [ ] Record actual lead time (order → in hand) vs quoted.
- [ ] Confirm written **breakage/replacement** terms.
- [ ] Lock the exact **order-intake format** (fields, photo delivery method) →
      feeds M3 email template in [`../build/architecture.md`](../build/architecture.md).
- [ ] Get pricing in writing at expected volumes → [`pricing-worksheet.md`](pricing-worksheet.md).
