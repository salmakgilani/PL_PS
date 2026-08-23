# Team Charter: Fable Growth

## Section 1 · Diagnose a Team Situation and Make a Call

### Name the situation

**Who they are (role, not name), what you have observed, and how long it has been happening:** The Product Owner on a delivery team. Observed behavior: not vocal in control board meetings — doesn't say no or reason through risk out loud — doesn't plan for delivery in depth, and shows gaps in domain knowledge that cause risks to be missed until late. This has been happening for more than 3 months.

### Make a diagnosis

**Your diagnosis, plus one sentence on why. Is your frustration with their behavior, or with a decision you made?**

Diagnosis: **System** — something in the structure or resourcing makes it impossible to perform.

Why: The gap traces back to a missing onboarding/knowledge-transfer process, not a mindset or fit problem — without structured domain KT, no PO could reliably assess and surface risk in board meetings. My frustration is with a decision I made (or didn't make): not putting a structured onboarding process in place for this role, not with the PO's behavior itself.

### One next action I will take in the next two weeks is…

Give feedback with clarity, and put in place an overall onboarding process with well-planned knowledge transfer for the domain.

### The first sentence of the conversation I need to have is…

"Let's work on the onboarding process, as we see that the expectations are not met."

---

## Section 2 · Fable Growth Cross-Team Charter

> Cross-team charter resolving ownership between Core Fable (you), PM1 (Onboarding), PM2 (Retention), PM3 (AI check-in layer), and Growth — written to fix the named tension: deliveries and dependencies are not transparent, and handshakes aren't happening.

### What We Own

**What this team owns:** The core Fable product experience — the calming content platform, overall product strategy and OKRs (KR1–KR3), and the shared usage-analytics and personalization engine that PM1, PM2, and PM3 build on top of.

**What is out of scope:** Onboarding flow execution (PM1), retention campaign execution (PM2), AI check-in prompt logic (PM3), habit-formation mechanics like the streak feature (Growth).

**Cross-boundary decisions that need a joint call:** Any change to the AI check-in layer that surfaces inside onboarding or retention, or any change to the shared analytics/personalization engine's core logic.

| Owner | Owns | Explicitly out of scope | Requires a joint call before action |
|---|---|---|---|
| **You (Core Fable)** | Overall product strategy and OKRs (KR1–KR3); the core calming content/experience; the shared platform capabilities named in the strategy — the usage/behavioral analytics engine and adaptive personalization engine that other pods build on top of. | Day-to-day execution of onboarding, retention, or AI check-in roadmaps — those belong to PM1/PM2/PM3. | Any change to the core logic of the shared analytics/personalization engine, since PM3's check-in layer depends on it directly. |
| **PM1 (Onboarding)** | The day-0 to acute-need-resolution surface — onboarding flow, activation. | Anything past acute-need resolution (that's PM2's surface). | Any AI check-in prompt that surfaces during onboarding (PM3's logic touching PM1's surface). |
| **PM2 (Retention)** | The post-activation, post-90-day surface — reactivation flows, retention-specific features. | Onboarding/activation mechanics (PM1's); day-to-day AI check-in logic (PM3's). | Any AI check-in prompt that targets retention-window users (PM3's logic touching PM2's surface). |
| **PM3 (AI check-in layer)** | The check-in engine itself — personalization logic, prompt content, timing/triggering rules. | The onboarding flow and retention campaign strategy — PM3 builds the layer that surfaces inside those surfaces, but doesn't own the surfaces. | Any change to *where or when* check-ins surface within onboarding (PM1) or retention (PM2); any change to the shared analytics engine (Core Fable's). |
| **Growth** | Habit-formation mechanics (e.g., the streak feature) — distinct from PM2's reactivation-flow ownership. | AI check-in logic (PM3's); onboarding (PM1's). | Any habit mechanic that touches the check-in layer or a retention flow. |

### How We Decide

**Who decides feature and scope calls:** Each PM decides scope within their own owned surface alone; shared surfaces (e.g., check-in prompts inside onboarding or retention) need a joint call between the owning PMs.

**How cross-team conflicts escalate:** If the two PMs can't agree within 2 business days of a written handshake, escalate to the Core Fable product lead for a decision.

**Who resolves escalations from outside the team:** The Core Fable product lead owns external/cross-initiative escalations, with a response within 48h.

- **Inside your own surface:** the owning PM/team decides unilaterally — no joint call needed.
- **Cross-boundary** (e.g., PM3 shipping a check-in change that touches PM1's or PM2's surface): the two owning PMs must agree via a written handshake — a short dependency note in the shared doc/channel, posted at least 3 business days before the dependent team's sprint or release. Not a verbal heads-up — it has to be written and timestamped, since "handshakes aren't happening" is the tension this charter is fixing.
- **If the two PMs can't agree within 2 business days** of the handshake being posted: escalate to you (Core Fable) as the deciding authority — since any real disagreement here is ultimately an OKR trade-off, which rolls up to the strategy you own.
- **If Growth has a stake in the same overlap:** Growth's input goes into the same handshake doc, but Growth doesn't hold veto power over PM1/PM2/PM3's owned surfaces — if Growth disagrees, it escalates to you, same as any other conflict.
- **Standing ritual:** a weekly cross-pod dependency sync where upcoming cross-boundary work gets flagged before it becomes a handshake-in-writing problem — this is the direct fix for the named tension, since it makes the handshake a scheduled, visible checkpoint instead of something easy to skip.
