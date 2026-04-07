# Power Curve Metrics: P3, P10 and P20

## What Are P3, P10 and P20?

**P3, P10 and P20** are your **maximum average power values** (in watts) achieved over 3, 10 and 20 minutes respectively during a running session.

- **P3** — Best average power over any continuous 3-minute window in the session
- **P10** — Best average power over any continuous 10-minute window in the session
- **P20** — Best average power over any continuous 20-minute window in the session

WbalPro calculates these values automatically throughout every run. They update continuously as the session progresses — including after pauses — so you always see the best effort recorded up to that moment.

---

## Why Do They Matter?

These three values form the **basis for calculating your Critical Power (CP) and W'** — the two core parameters that WbalPro uses to model your energy balance in real time.

According to sports science literature, performing maximal efforts at three different durations between 3 and 20 minutes is sufficient to derive an accurate CP and W' estimate. P3, P10 and P20 are exactly those three reference points.

> Without accurate CP and W' values, the W'bal model cannot reflect your true physiology.

---

## How to Record and Use Them

### Step 1 — Run and let WbalPro calculate

Every time you run, WbalPro tracks your best power windows. After the session, note down:

| Metric | Value (W) |
|--------|-----------|
| P3     |           |
| P10    |           |
| P20    |           |

### Step 2 — Keep a record over 45–60 days

Your P3, P10 and P20 will improve as you train. **What matters for calculating CP and W' are your all-time maximums** (or maximums within the last 45–60 days, to reflect current fitness).

Keep a simple log — a note, a spreadsheet, anything — and update it whenever you beat a previous best.

### Step 3 — Calculate your CP and W'

Once you have your best P3, P10 and P20, plug them into this free online calculator:

🔗 **[High North Critical Power Calculator](https://www.highnorth.co.uk/critical-power-calculator)**

Enter:
- **Test 1:** 3 minutes → your P3 value
- **Test 2:** 10 minutes → your P10 value
- **Test 3:** 20 minutes → your P20 value

> ⚠️ The calculator asks for duration **in seconds**, not minutes. Enter 180, 600 and 1200 respectively.

The calculator will output your **Critical Power (W)** and **W' (kJ)**. Enter those values into WbalPro settings.

---

## How Often Should You Recalculate?

Recalculate CP and W' **every 6–8 weeks**, or whenever your fitness changes significantly (after a training block, after an injury break, etc.).

Your P3, P10 and P20 update automatically every session — you just need to track your maximums and re-run the calculation periodically.

---

## Behaviour During a Session

- Values are calculated **continuously** throughout the run
- A **pause does not reset the calculation** — WbalPro keeps tracking from where you left off
- The values shown are always the **best window recorded so far** in the current session

---

## Related Topics

- [What is Critical Power?](../01-concepts/critical-power.md)
- [What is W'?](../01-concepts/w-prime.md)
- [W'bal explained](../01-concepts/wbal-explained.md)
- [Metrics overview](metrics-overview.md)
