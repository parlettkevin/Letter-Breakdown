# Product

## Register

product

## Users

**Primary**: Loan officers at DML (mortgage lender) — Kevin Parlett and Corey Glowacki. Used on a phone, mid-call, often outdoors or away from a desk. The prototypical scenario: at a son's lacrosse game on a Saturday when a borrower calls asking for numbers and a letter. The alternative is finding a laptop and making the borrower wait. This tool eliminates that wait.

**Job to be done**: Stay on the phone, enter a handful of numbers, read a monthly payment figure aloud, then get a pre-approval PDF emailed to the borrower before hanging up. The borrower almost never sees the screen — the loan officer is reading numbers aloud and emailing a document.

## Product Purpose

A fast, phone-first mortgage calculator and pre-approval letter generator for active loan officers. Success means a loan officer can complete the full workflow — calculate a payment, generate a letter, email it — while staying on a call, without going to their car for a laptop.

Two co-equal outputs:
1. **Pre-approval PDF** — downloaded and shared from the phone via Web Share API
2. **Copy-to-SMS summary** — plain-text loan summary pasted into iMessage or text

## Brand Personality

**Three words**: Swift, grounded, trusted.

- **Swift**: Every friction point costs the officer credibility with a live borrower on the line.
- **Grounded**: Warm neutrals, not cold blues or gradients. This is serious money work.
- **Trusted**: Competent and authoritative without being intimidating. Looks like a real professional built it for themselves.

## Anti-references

- Real estate listing sites — busy, image-heavy, card-grid aesthetic
- Generic bank portals — cold, corporate, forms-heavy with no personality
- Trendy fintech apps — dark gradients, neon accents, style over data density

**Target feel**: A well-made field instrument — a premium handheld calculator, a clinical intake form at a high-end medical practice, a surveyor's app. Functional, legible, slightly warmer than clinical.

## Design Principles

1. **Mobile speed first** — designed for use while on a phone call. Every interaction must work with one thumb on a 6-inch screen, outdoors, half-distracted.
2. **Two outputs, one flow** — PDF email and SMS copy are co-equal deliverables. Neither is secondary.
3. **Scan before you read** — the officer is half-listening. Monthly payment and cash-to-close totals must pop at a glance without being distractingly large.
4. **Restraint signals trust** — the orange accent is rare and intentional. Overuse makes it a busy consumer app; restraint makes it feel like a professional tool.
5. **Reduce scroll before Calculate** — secondary inputs (letter dates, escrow cushion, government fee adjustments) should be collapsed by default so the primary workflow stays fast.

## Accessibility & Inclusion

No formal WCAG compliance target (internal tool, two named users). Functional accessibility practices in place: 16px+ font sizes prevent iOS zoom, 44px minimum tap targets, `prefers-reduced-motion` respected on all animations. Maintain these as floors; no audit target required.
