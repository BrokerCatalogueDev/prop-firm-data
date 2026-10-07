# Prop firm rules, fees and regulator log

By [BrokerCatalogue](https://brokercatalogue.com/prop-firm-data/). Version 1, 29 September 2026. Licence: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

Two files. One lists the rules, fees and payout terms of 76 prop trading firms. The other is a dated log of what regulators have said and done about prop firms. Every row names its source.

- Canonical page, always the latest: https://brokercatalogue.com/prop-firm-data/
- `bc-prop-firms-v1-2026-09-29.csv`: 76 firms, 28 columns, UTF-8. Firm facts checked 24 September 2026. SHA-256 `c2c3ecd2563ff6d712889dd64d5141ab112b1d109c4459a5b748263658440be8`
- `bc-prop-firm-regulator-log-v1-2026-09-29.csv`: 13 entries from March 2024 to September 2026, 9 columns. Checked 28 September 2026. SHA-256 `359e37cd9aca282b2a2ddb80ddefd4a0c6db72384a689ce7e251b6e55ac8bbaf`
- DOI: https://doi.org/10.5281/zenodo.23205561 (version 1.0.0). All versions: https://doi.org/10.5281/zenodo.23205560

Version 1 counts: 65 active, 5 watch and 6 closed firms. Confidence: 45 high, 29 medium, 2 low. Regulator log: 10 regulator entries and 3 industry entries.

## Columns: prop firm rules and fees

| Column | Meaning |
|---|---|
| slug | Our ID for the firm (the end of its profile URL). |
| name | Firm name. |
| website | Official website. |
| status | active, watch (something changed that you should read about first) or closed (stopped selling challenges). |
| status_note | Why a firm is on watch or closed. |
| founded | Year founded, as stated by the firm or a named second source. |
| hq_city | City where the firm says it is based. |
| hq_country | Country where the firm says it is based. |
| models | Challenge models: one-step, two-step, three-step, instant-funding. Several values are separated by \|. |
| assets | Markets: forex, indices, commodities, crypto, futures, stocks. Separated by \|. |
| platforms | Trading platforms. Separated by \|. |
| max_allocation | Largest account or combined allocation offered. |
| profit_split | Trader share of profits. |
| challenge_fee_from | Lowest challenge fee we found, with the account size or condition it depends on. |
| account_sizes | Account sizes offered. Separated by \|. |
| payout_frequency | How often the firm pays. |
| daily_drawdown | Daily loss limit. |
| max_drawdown | Maximum loss limit. |
| min_trading_days | Minimum trading days to pass. |
| time_limit | Time limit to pass, if any. |
| news_trading | yes, restricted or unknown. |
| weekend_holding | yes, no, restricted or unknown. |
| ea_allowed | Expert advisors (trading robots): yes, no, restricted or unknown. |
| broker_backing | Broker or liquidity provider named by the firm. |
| sources | Links we used. Separated by \|. |
| confidence | high, medium or low. Lower when a figure came from a second source. |
| checked_on | Date we checked (YYYY-MM-DD). |
| profile_url | Our profile of the firm. |

## Columns: regulator log

| Column | Meaning |
|---|---|
| date | Date of the statement or event (YYYY-MM-DD). |
| date_text | The same date in words. |
| country | Country or region. |
| who | Who acted. |
| type | regulator or industry (a change made by firms, not an act of a regulator). |
| what_happened | What happened, in plain English. |
| source_name | The document or report we used. |
| source_url | Link to it. |
| checked_on | Date we checked (YYYY-MM-DD). |

## Sources and method

We read each firm's own website first: its rules, its fee page and its terms. When a site would not load or hid a figure, we used a named second source and gave the row a lower confidence rating. We do not check single payouts, and we cannot promise that any firm will pay you. The regulator log links each statement or report.

## Versions

This is version 1, a fixed copy from 29 September 2026. It will not change. Firm rules change often, so always check the live page for the newest data: https://brokercatalogue.com/prop-firm-data/

If we ever add a new version here, it gets a new file name and a line in CHANGELOG.md.

## How to cite

BrokerCatalogue (2026). *Prop firm rules, fees and regulator log*, version 1 (29 September 2026) [Data set]. https://brokercatalogue.com/prop-firm-data/ . DOI: 10.5281/zenodo.23205560

## Licence

CC BY 4.0. Please credit "BrokerCatalogue" and link to https://brokercatalogue.com/prop-firm-data/. Copyright 2026 Catalinq LLC.

## Limits

Information only, not investment advice. Prop firm challenges cost money, and many buyers do not pass. Check the firm's own site before you pay.

## Who publishes this

BrokerCatalogue is run by Catalinq LLC. We may earn a commission through links on other pages of our site. This dataset has no such links, and no firm can pay to change it. Firms can ask us to fix a fact at https://brokercatalogue.com/claim/.
