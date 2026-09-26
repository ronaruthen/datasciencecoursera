# ILA Hub — 6-month revenue model (Oct 2026 – Mar 2027)

Daniel McAfee as sole provider. 18–22 ILA slots per week. Prices £150 Essential, £190 Priority, £25 wet-signature add-on.
Built 26 Sep 2026 from the live case database, the Master PRD commercial terms, and the September founder catch-ups.

Workbook: `ILA_Hub_Revenue_Model_Oct26-Mar27.xlsx` (formulas throughout; recalculates on open).

## Answer

| Scenario | Slots/wk | Fill ramp | Refund | 6-mo net delivered revenue | Avg / month | Mar-27 run-rate | Daniel 60% | Rona 40% | Daniel hrs/wk |
|---|---|---|---|---|---|---|---|---|---|
| Low | 18 | 40% → 60% | 15% | £30.0k | £5.0k | £6.4k | £17.1k | £11.4k | 3.6 → 5.5 |
| Base | 20 | 50% → 80% | 10% | £46.5k | £7.7k | £10.1k | £25.3k | £16.9k | 5.0 → 8.0 |
| High | 22 | 60% → 90% | 7% | £63.2k | £10.5k | £13.1k | £34.0k | £22.7k | 6.6 → 9.9 |

Shares are of distributable net after Stripe, e-signature, AI, postage and marketing (PRD §2).

## Month by month, net delivered revenue (£)

| | Oct | Nov | Dec | Jan | Feb | Mar |
|---|---|---|---|---|---|---|
| Low | 4,318 | 4,594 | 3,625 | 5,657 | 5,380 | 6,443 |
| Base | 6,331 | 7,222 | 5,634 | 8,518 | 8,653 | 10,107 |
| High | 8,775 | 9,811 | 7,575 | 11,932 | 11,932 | 13,132 |

## What the numbers say

- **Fill, not capacity, is the constraint.** 20 slots × 4.3 weeks × £150 is ~£12.9k/month gross at full fill. Actual fill since mid-August is 30–45% (6–15 paid cases/week, average 9). Low is today's run-rate carried forward.
- **£6k/month is a fill problem; £10k/month is a March-only outcome at 20 slots.** Base clears £6k from October and only touches £10k in March. High clears £10k from January. Neither needs more than 10 hours a week of Daniel's time.
- **Refunds are the largest controllable leak.** 13% by count since August, 20.7% lifetime by value. Every 5 points is ~£400/month at Base volumes. Lender library and pack-check intake are the fixes already in flight.
- **Priority is unsold.** One Priority booking since repricing. The model assumes 5–15% mix; if it stays near zero, subtract ~£150–£500/month.
- **VAT threshold arrives inside the window on Base and High.** Base annualises to ~£121k by March against the £90k rolling threshold. Decide before January whether £150 becomes £180 inc. VAT or the margin absorbs it.
- **December is thin by design** (3.0 working weeks). Working through Christmas adds ~£2.6k on Base.

## Calibration (Actuals sheet, production DB)

| Week of | Paid | Delivered | Refunded | Unpaid holds | Paid £ |
|---|---|---|---|---|---|
| 17 Aug | 15 | 7 | 6 | 2 | 1,800 |
| 24 Aug | 7 | 4 | 0 | 8 | 840 |
| 31 Aug | 13 | 5 | 1 | 6 | 1,890 |
| 7 Sep | 6 | 3 | 0 | 6 | 900 |
| 14 Sep | 6 | 6 | 0 | 0 | 900 |
| 21 Sep | 6 | 4 | 0 | 6 | 940 |

Tier mix since 1 Aug (paid): 20 legacy £120, 24 Essential £150, 1 Priority £190. Booking peak is Tue–Thu 12:00 UK.

## Assumptions you can change (yellow cells, Assumptions sheet)

Slots per week, monthly fill ramp, refund rate, Priority mix, wet-sign uptake, ads spend, working weeks per month, unit costs, revenue split.

## Known gaps

- Daniel's committed weekly slots were never recorded (dashboard item D12); the 18–22 range is the input.
- Revenue is booked in the month paid. Delivery lags by days to weeks, so individual months are slightly optimistic; the 6-month total is not affected.
- Second-guarantor bookings are treated as ordinary slots, no separate uplift.
- Additional lawyers (2–3 targeted by November in the catch-ups) are excluded per the brief.
