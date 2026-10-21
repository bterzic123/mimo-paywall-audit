# Paywall Audit — Mimo

**Live:** https://bterzic123.github.io/mimo-paywall-audit/
(prototype directly: https://bterzic123.github.io/mimo-paywall-audit/?open=proto)

Four ranked ideas for Mimo's Pro paywall and the offer it shows on close. Each idea is backed by a number from Adapty's **State of Paywalls 2026**. The page also scores the paywall against the report and includes a clickable rebuild in Mimo's own design, with a Today / Proposed switch and numbered report pins.

| # | Idea | Report anchor | Outcome shown |
|---|---|---|---|
| 1 | Name the yearly plan and show its price | 5.3 “Trial on annual, emphasized”; 3.3 62% show full annual price | CR +15–30% (observed in winning A/B tests) |
| 2 | Put the 4.8 stars (110K ratings) on the paywall | 5.3 Social proof on the paywall; 3.1 only 27% use it | CR +10–30% (observed in winning A/B tests) |
| 3 | Use onboarding answers in the headline | 5.3 Onboarding personalization; 3.5 only 2% personalize | CR +8–17% (observed in winning A/B tests) |
| 4 | Show the saving on the close offer, not a code | 4.5 second-chance: 4% of apps, beats main in 45%; 2.7 ≤30% off keeps 90% of revenue | Finding only, no range |

**Slice:** Education · US (Mimo's largest App Store market by revenue). App Store data, Oct 2025–Sep 2026. Design shares come from the report's 100 top iOS paywalls (patterns, not performance).

**Report:** https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=mimo

**Grounding.** Prices (74,99 €/year, 6,24 €/month, 4,99 € first month, 59,99 €/year after 14 days free), the trial timeline and the WELCOME25OFF offer all come from Mimo's live iOS paywall, recorded on a euro storefront in October 2026. The rating (4.8 · 110K) and the New York Times line come from Mimo's US App Store listing. The four Pro lines come from Mimo's own pre-paywall screen. Light mode is an approximation, because Mimo ships dark.

Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and Adapty's own data, not measured results for Mimo.

Run locally: `python3 -m http.server` in this folder, then open http://localhost:8000.
