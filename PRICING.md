# Trelix Translator — Pricing

All prices in USD; local equivalents are determined by Apple App Store pricing tiers.

## Auto-renewable subscriptions

| Plan       | Price       | Trial         | StoreKit Product ID    |
|------------|-------------|---------------|------------------------|
| Weekly     | $4.99 / wk  | 3-day free    | `translate.sub.week`   |
| Monthly    | $9.99 / mo  | —             | `translate.sub.month`  |
| Yearly     | $39.99 / yr | —             | `translate.sub.year`   |

> Yearly equals ~$3.33/mo — about 67% off the monthly plan and ~85% off the weekly plan. This is the headline anchor on the paywall.

## Free tier

Available without subscription:
- Text translation (unlimited, on-device)
- Up to 10 voice translations / day
- Up to 5 camera (OCR) translations / day
- 1 offline language pack

## Premium unlocks

- Unlimited voice and camera translations
- Unlimited offline language packs
- Dialogue (two-way) mode
- Translation history without cap
- No ads, priority OCR

## Notes for App Store Connect

- Subscription group: `Trelix Premium`
- All three products belong to the same group → upgrade/downgrade is automatic.
- 3-day trial is configured as an *Introductory Offer → Free* on the **weekly** product only, eligibility = "New Subscribers".
- Family Sharing: **off** (single-user license).
- Localized prices: leave Apple auto-conversion on; review RU, EUR, PLN tiers manually.
