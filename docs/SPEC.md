# SubSpot: Spec

**Every subscription, renewal and free trial in one place** · #14 of 33 · Wave 2: Recurring keepers · Used: Monthly · Easy · Revenue potential: Medium–high · Money & Work · Source: ChatGPT + Perplexity

## One-liner

List your subscriptions (streaming, gym, apps, phone contract, insurance) and SubSpot shows the real monthly and yearly total, warns you before renewals and free-trial endings, and keeps a 'cancel before renewal' list.

## Problem / audience

- **Who it's for:** Anyone with several subscriptions.
- **The problem it solves:** Subscriptions renew quietly, free trials convert to paid, and nobody knows their real monthly total.
- **Example:** A user adds everything, sees £87 a month, and cancels two services before they renew.

## MVP features (ship with only these)

1. Quick add with common services pre-filled
2. Monthly, yearly and per-use cost
3. Renewal and trial-ending reminders
4. 'Cancel before renewal' list
5. Total recurring spend dashboard

## Not in MVP

- Spending insights and categories
- Shared household subscriptions
- Yearly recap card

## Monetisation

| Model | Detail |
|---|---|
| Free | Up to 5 subscriptions, with ads |
| Premium | £1.99–£2.99/month: unlimited, reminders, insights, sharing |
| Ads | Light, never on the totals screen |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Renewal and trial reminders |
| Tiny win | Keep or cancel in one tap |
| Progress | Money saved by cancelling |
| Share | 'I was spending £X a year' card |
| Next step | Monthly check-in: anything new? |
| Cadence | Event-driven, monthly |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone

**Calm.** Smooth, reassuring motion only: gentle ticks, numbers easing into place. No characters, jokes or drama.

- A cancelled subscription card slides away and the yearly saving ticks up


## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app (needs notifications).
- **Data:** On the device only. No bank connection.
- **Backend:** None for the free version: everything lives on the phone. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Subscription creep; Free-trial traps; Keep or cancel
- **Shareable output:** 'I was spending £X a year' card

## Risks

Use is episodic, so reminders are essential. Recurring-date maths must handle every billing cycle correctly.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
