# Outcome Roadmap & Trade-off Memo: [Fable / Meridian / your initiative]

> Module 2 · Prioritization & Roadmapping for Product Leaders, ★ Deliverable 2
>
> Translate your strategy into a multi-team, outcome-driven roadmap, and a memo defending the hard prioritization calls behind it.

## 1. Outcome roadmap

_A multi-team roadmap organized by **outcomes**, not feature lists. Show how near-term revenue pressure is balanced against long-term platform bets._

**This quarter's problem:** users resolve their acute need on Fable within 90–120 days, then quietly stop opening the app. Every Now bet below is aimed at keeping them past that point.

### Now (0 to 3 mo) — strategic bets, not delivery milestones

| Bet | OKR it moves | Owning team | Item / Source |
|---|---|---|---|
| We bet personalizing daily check-in prompts to a user's own history will extend engagement past the point their original need resolved, for users approaching or past their 90-day mark. | KR1 (90-day+ retention: 15%→30%) and KR3 (180-day retention: 10%→22%) | Product | Item 6, Product |
| We bet turning app-opening into a repeatable daily habit, rather than a need-driven visit, will keep users returning after their acute problem fades, for users who have already resolved their acute need. | KR1 (90-day+ retention: 15%→30%) | Growth | Item 2, Growth team |
| We bet fixing broken re-engagement notifications (wrong times, timezone errors) will recover a meaningful share of users who would otherwise churn silently, for users who have gone quiet in the day 91–120 window. | KR2 (day 91–120 reopen/reactivation: 8%→20%) | Engineering | Item 4, Engineering |

### Next (3 to 6 mo) — sequenced after Now

| Item | Source | Why it comes after Now |
|---|---|---|
| WCAG 2.1 accessibility fix | Legal | Mandatory, but doesn't draw on the same OKR-focused capacity as the Now bets — sequenced right behind them so it doesn't compete with the retention experiments. |
| Reduce load time to <2s on 4G | Engineering | Compounds on top of the Now bets rather than replacing them — worth investing once we know which mechanics (personalization, streaks) are the right things to make fast. |
| Content library expansion | Content team | Better sequenced after the personalization bet ships, so content investment is guided by what it reveals users actually need post-acute, not built blind. |
| Onboarding redesign (40% drop-off) | Product analytics | Real problem, but targets day-0 drop-off, not the day-90–120 retention crisis this initiative owns — would compete with the Rocks for the same design/PM capacity. |

### Later (6 to 12 mo) — strategic bets, not commitments

| Item | Source | Why it's a future bet |
|---|---|---|
| Social layer (share progress) | User research | Plausible, but unconfirmed by the strategy — worth testing only after the personalization bet proves out. |
| Localize Spanish/Portuguese | Sales (LATAM) | Expands into a new market outside this initiative's "where to play" (existing 25–45 base) — not this initiative's job. |
| Web version | Community | Unproven relationship to retention — revisit once Now-horizon data exists to justify the build. |
| Apple Watch integration | Partnership requests | Partner interest isn't evidence of retention impact — revisit once there's data on which engagement mechanics actually work. |

_Items 5, 9, and 13 — the therapist-matching premium tier, crisis-mode flow, and "Fable for Teams" B2B — are excluded entirely, not deferred to Later, since they conflict with the strategy's hard no or "where to play," not just resourcing. See Hard Nos below._

### Hard Nos — item, source, and why not this quarter

- **Hard No #1 (Item 5):** Premium tier with therapist-matching — CEO. Despite coming from the loudest source on the list, it directly violates the hard no from Deliverable 1: no repositioning as a clinical platform.
- **Hard No #2 (Item 13):** "Fable for Teams" B2B workplace wellbeing — Business dev. Falls entirely outside "where to play" (adults 25–45, individual use case) — different customer, different motion, zero connection to this quarter's OKR.
- **Hard No #3 (Item 9):** "Crisis mode" flow for acute anxiety — Clinical advisor. Serves the acute phase, which the brief says Fable already does well — the opposite problem from the diagnosed retention crisis, and risks the same clinical-adjacency the hard no already ruled out.

_[screenshot or shareable link to your roadmap visual]_

## 2. Trade-off memo

_What did you sequence first, what did you push out, and what did you cut entirely, and why? Use WSJF / cost of delay reasoning where it helps._

> I chose to sequence personalized daily check-ins, the streak feature, and the notification fix first because they're the only three items on the backlog that directly move this quarter's OKRs (KR1, KR2, KR3) — and together they attack the actual diagnosed problem (users going quiet after their acute need resolves), not adjacent problems like onboarding drop-off or new-market growth.
>
> I pushed out the WCAG accessibility fix, load-time reduction, content library expansion, and onboarding redesign because each is legitimate work that competes for the same engineering/design/PM capacity as the three Rocks, without moving this quarter's retention OKRs directly — they're sequenced right behind Now rather than cut, since nothing here conflicts with the strategy, it's a capacity call, not a strategic one.
>
> I cut entirely the therapist-matching premium tier, the B2B "Fable for Teams" play, and the crisis-mode flow because each one conflicts with the strategy itself, not just this quarter's bandwidth: therapist-matching violates the explicit hard no against clinical repositioning, "Fable for Teams" targets a different customer outside "where to play," and crisis-mode serves the acute phase the brief says Fable already handles well — the opposite of the retention problem this initiative exists to solve.

## Link to full artifact

_[link to Slide 2 of your deliverables deck]_
