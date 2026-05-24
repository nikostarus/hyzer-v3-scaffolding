# Hyzer v3 Second-Pass Review Checklist

Use this for a fast, brutal pass. Mark each item as `PASS`, `FIX`, or `CUT`. If unsure, default to `FIX`.

## 0. Review posture

- [ ] Does the page feel like a market-entry / demand-capture funnel, not a generic SaaS/product site?
- [ ] Can a cold reader understand the wedge in 10 seconds: July moment + creators/operators + early-access capture?
- [ ] Is every section doing one of these jobs?
  - explain why July matters
  - establish Hyzer as the serious operator/creator play
  - capture early-access demand
  - give influencers/operators a clean story to forward
- [ ] Is anything trying to explain the whole future product? If yes, cut or park it.

## 1. Above-the-fold brutality

- [ ] H1 is specific, urgent, and tied to the market window.
- [ ] Subhead says who it is for: operators, creators, distribution/partner teams.
- [ ] Subhead says what Hyzer does without drifting into vague “infra” language.
- [ ] Primary CTA is early access / apply, not demo/access/sales.
- [ ] Secondary CTA supports influencer brief or operator pilot.
- [ ] No reader should ask: “Wait, what is this actually?”

Failure triggers:
- [ ] Sounds like generic launch software.
- [ ] Sounds like regulated service/care operations.
- [ ] Sounds like a complete mature broad product noun.
- [ ] July is only decorative instead of structurally driving the page.

## 2. Positioning sharpness

- [ ] Hyzer is framed as a July-window launch / demand-capture layer.
- [ ] The phrase “launch system/layer” feels concrete because surrounding copy names actual motions: creator education, intake, partner routing, early-access capture, launch coordination.
- [ ] Avoids empty abstractions: “broad system noun,” “ecosystem,” “operating system,” “all-in-one,” “broad product noun” unless heavily qualified.
- [ ] Does not over-index on internal mechanics instead of public conversion.
- [ ] The page feels built for serious operators preparing before the spike, not tourists browsing later.

Brutal question:
- [ ] Would a strong creator/operator know why to apply today instead of bookmarking and forgetting?

## 3. Claims / compliance risk

Hard fail if public copy implies Hyzer provides:
- [ ] regulated care
- [ ] regulated advice
- [ ] Rx operations
- [ ] regulated services
- [ ] legal advice
- [ ] payment operations
- [ ] logistics operations
- [ ] regulated logistics operations
- [ ] qualified partner networks
- [ ] guaranteed regulatory outcome
- [ ] guaranteed July result
- [ ] creator permission to make health/product claims

Required guardrails:
- [ ] Hyzer is not positioned as the regulated provider.
- [ ] Regulated or operational claims stay with qualified partners/responsible parties.
- [ ] July language is “decision window / market moment,” not a promised outcome.
- [ ] Creator language says education-led, guardrails, routing — not claims or hype.

## 4. CTA / funnel integrity

- [ ] Homepage routes only to early access / access tracks / operator pilot / creator brief.
- [ ] Plans page is access tracks, not fake access.
- [ ] Contact page captures role, audience/company/channel, interest, and why-now context.
- [ ] CTA copy is consistent: request early access, apply for pilot, request influencer brief, start partner conversation.
- [ ] No “Book a demo,” “Start free trial,” “See access,” or enterprise-sales leftovers.
- [ ] Form destination is known. If still `mailto:`, mark as temporary blocker before public launch.

## 5. Placeholder / route containment

- [ ] Public nav exposes only approved funnel pages.
- [ ] Secondary routes are not linked from public funnel CTAs.
- [ ] Secondary routes contain `noindex,nofollow`.
- [ ] Secondary routes visibly say coming soon / review pending.
- [ ] Secondary route copy does not accidentally sell modules, products, or claims.
- [ ] Legal/privacy/terms routes are clearly review-pending, not fake finalized policies.
- [ ] No hidden legacy nav/mega-menu remains in markup.

Route classes to inspect:
- [ ] homepage: `index.html`
- [ ] access tracks: `plans/index.html`
- [ ] intake: `contact/index.html`
- [ ] coming-soon company/brief/legal: `about`, `blog`, `legal/*`
- [ ] coming-soon legacy modules: builder, integrations, signal assistant, order/payment/security/etc.

## 6. legacy structure term residue grep

Run / verify scans for these terms in public-facing files:

- [ ] `legacy brand term`
- [ ] `reference brand term`
- [ ] `reference brand lowercase`
- [ ] `legacy structure term`
- [ ] `legacy structure lowercase`
- [ ] `regulated-category term`
- [ ] `clinician term singular`
- [ ] `clinician term singulars`
- [ ] `Rx operations`
- [ ] `e-Rx operations`
- [ ] `regulated logistics term`
- [ ] `regulated logistics plural`
- [ ] `logistics term`
- [ ] `privacy acronym`
- [ ] `payment acronym`
- [ ] `care-user term singular`
- [ ] `care-user term singulars`
- [ ] `regulated-care adjective`
- [ ] `regulated-service adjective`
- [ ] `regulated-category noun`
- [ ] `broad product noun`
- [ ] `broad system noun`
- [ ] `draft=`
- [ ] links to coming-soon legacy routes from public funnel HTML

Allowed exceptions must be explicitly named and justified. Route filenames alone are not public copy, but public links to those routes are a problem.

## 7. Page-by-page checks

### Homepage
- [ ] H1 is strong enough to carry the page.
- [ ] July hook appears early and repeatedly with purpose.
- [ ] Creator angle is concrete.
- [ ] Operator angle is concrete.
- [ ] Partner routing is conservative.
- [ ] No CTA routes to coming-soon modules.
- [ ] The final CTA reinforces early access.

### Access tracks
- [ ] Clearly says “not access yet.”
- [ ] Creator Partner track is useful and education-led.
- [ ] Operator Pilot track is the strongest/default track.
- [ ] Partner Track is conservative and does not imply unverified capabilities.
- [ ] FAQ answers are precise and not over-defensive.

### Contact / intake
- [ ] Form fields capture useful qualification signal.
- [ ] Guardrail copy is clear but not scary.
- [ ] Button submits somewhere real or is flagged as temporary.
- [ ] The page makes the ask feel selective, not generic.

### Coming-soon routes
- [ ] Every coming-soon page says coming soon/review pending.
- [ ] Every coming-soon page points back to early access/access tracks only.
- [ ] No coming-soon page introduces new module promises.
- [ ] No coming-soon page has finalized legal/compliance language.

## 8. Mobile/nav sanity

- [ ] Mobile nav opens and remains readable on dark background.
- [ ] Nav has no dropdown/mega-menu leftovers.
- [ ] Buttons do not wrap into nonsense on narrow widths.
- [ ] Primary CTA is reachable without hunting.
- [ ] Coming-soon route notice does not break nav layout.

## 9. Copy cuts

Cut or rewrite anything that sounds like:
- [ ] “We do everything.”
- [ ] “We are the regulated/care layer.”
- [ ] “We have mature enterprise broad system noun.”
- [ ] “July will definitely produce X.”
- [ ] “Creators can safely make claims.”
- [ ] “Operators can launch without qualified partners.”
- [ ] “This is just software for software’s sake.”

## 10. Final reviewer output format

Use this exact structure for the second-pass report:

```md
# Hyzer v3 Second-Pass Review

## Verdict
SHIP / FIX FIRST / DO NOT SHIP

## Highest-risk blockers
1.
2.
3.

## Positioning fixes
- 

## Claims / legal-risk fixes
- 

## Coming-soon route fixes
- 

## CTA / funnel fixes
- 

## Copy line edits
- `old` → `new`

## Grep / verification notes
- 
```
