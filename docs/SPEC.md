# SubSpot: Spec

**Rank in portfolio:** #8 of 15 (easiest → hardest) · **Difficulty:** Easy

## One-liner

Track every subscription, renewal date and what you really spend each month.

## Problem / audience

- **Who it's for:** Anyone with too many subscriptions and a feeling they're overpaying.
- **The problem it solves:** Subscriptions renew quietly; people forget free trials and lose track of the monthly total.

## MVP features (ship with only these)

1. Add subscriptions (name, price, cycle, renewal date)
2. Monthly and yearly total
3. Renewal reminders (trial ending, renewal in 3 days)
4. Common services pre-filled

## Not in MVP

- Spending insights
- Shared subscriptions (household)
- Category breakdown

## Monetisation

| Model | Detail |
|---|---|
| Free | Up to 5 subscriptions, with ads |
| Paid | £1.99/month: unlimited + reminders + insights |
| Ads | Light; never on the totals screen |

Prices are starting points from the portfolio brief; test before committing.

## Platform & stack

- **Platform:** Expo (needs notifications).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob). See the portfolio roadmap.
- **Data:** Device only. No bank connection.

## Growth engine hooks

- **Shareable output:** "I spend £X a year on subscriptions" card.
- **Content pillars:** Subscription creep; Free-trial traps; Cancel-or-keep decisions

## Notes

Recurring-date maths (monthly, annual, custom cycles) must be correct.

## Launch checklist

- [ ] Name checked on App Store / Play Store / trademark search
- [ ] MVP features done and tested
- [ ] Privacy policy + terms
- [ ] Landing page
- [ ] Analytics wired
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
