# Research and Costing

## Source hierarchy

Use sources in this order:

1. Current provider terms, fee schedules, product pages, and official FAQs
2. Current prospectus, key facts statement, factsheet, or offering document
3. Exchange or regulator pages
4. Issuer or index-provider methodology pages
5. Reputable secondary explanations only for context

Do not use a search-result snippet as evidence. Open the page or document. For PDFs, inspect the relevant page and preserve the direct URL.

For each claim, record:

| Field | Required content |
|---|---|
| Claim | The exact rule or number used |
| Source title | Official page or document title |
| URL | Direct link, not a search page |
| Effective date | If the source provides one |
| Verified on | The date checked |
| Scope | Currency, account type, share class, customer group, or promotion |

If two official pages disagree, prefer the newer and more specific document. State the uncertainty rather than silently choosing a favorable number.

## Normalize the comparison

Define before calculating:

- `P`: average capital or holding value
- `r`: annual product charge rate
- `F(P)`: annual platform/account fee, including tiers
- `T`: holding period in years
- `C(P, T)`: visible cost over the period

Use:

`C(P, T) = T × (F(P) + P × r)`

If a fee is monthly, convert it to an annual amount only when the assumptions imply twelve chargeable months. If holding or trading activity determines whether the fee applies, show the assumed number of chargeable months.

For a tiered platform:

1. Identify whether the threshold uses purchase amount, month-end value, or average daily holding.
2. Apply the correct branch of `F(P)` at each scenario.
3. Warn that market movement can push a holding across the threshold.

## Find a break-even point

For two products with fixed fees `F1`, `F2` and annual rates `r1`, `r2`, solve:

`F1 + P × r1 = F2 + P × r2`

When `r1 != r2`:

`P* = (F2 - F1) / (r1 - r2)`

Check that `P*` falls inside the fee tiers used to derive it. If it crosses a tier boundary, solve again within each valid interval. Label the result “visible-fee crossover under these assumptions”.

## Scenario table

Use rounded amounts that help a reader locate themselves without revealing the user's balance. A useful default is:

| Capital | Route A | Route B | Route C | Interpretation |
|---:|---:|---:|---:|---|
| about 10k | cost / rate | cost / rate | cost / rate | Fixed fees dominate or do not apply |
| 20k | cost / rate | cost / rate | cost / rate | Small crossover may appear |
| 50k | cost / rate | cost / rate | cost / rate | Research low-rate alternatives |
| 100k | cost / rate | cost / rate | cost / rate | Rate differences become material |
| 200k | cost / rate | cost / rate | cost / rate | Re-check fee tiers |

Do not hard-code this pattern if the product thresholds or currency make other points more informative.

## Mandatory caveats

Unless calculated from verified inputs, exclude and disclose:

- foreign-exchange spread and conversion timing;
- bid-ask spread and market impact;
- market levies, custody, transfer, or dividend-processing fees;
- withholding, estate, income, or capital-gains tax;
- tracking difference and securities-lending effects;
- promotional rebates, rewards, and eligibility changes;
- partial-year holding and irregular trading;
- market return and risk.

Never label the lowest visible cost as the best investment. Cost, exposure, liquidity, tax, convenience, and behavior are separate decision dimensions.

