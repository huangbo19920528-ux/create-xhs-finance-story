---
name: create-xhs-finance-story
description: Turn a real banking, account-opening, financial-product, fund, ETF, deposit, fee-comparison, or investing experience into a sourced, privacy-safe Xiaohongshu/RedNote post and multi-page card story. Use when the user needs an account-opening walkthrough or failure self-check, current official-rule research, fact-versus-experience labeling, comparable cost scenarios and break-even thresholds, a non-promotional first-person narrative, concise title/body/hashtags, page-by-page card copy, screenshot redaction, official visual sourcing, mobile-first visual QA, source links, or publishing-setting advice.
---

# Create XHS Finance Story

## Overview

Convert one person's banking or financial-product experience into a clear, reproducible Xiaohongshu post without turning it into product promotion, unsupported troubleshooting advice, or personalized investment advice. Keep the dated lived experience central, verify unstable facts from current official sources, distinguish facts from hypotheses, separate visible costs from expected returns, and remove private account data.

## Workflow

### 1. Frame the real decision

Capture only the context needed to understand the choice:

- What account, cash balance range, or product prompted the decision?
- What does the person want to preserve: liquidity, account activity, fee benefits, diversification, or convenience?
- What are they deliberately avoiding: concentration, lock-up, currency conversion, direct stock selection, or high fixed costs?
- What existing exposure changes the decision?
- What time horizon and loss tolerance apply?
- What happened, on which date, and which settings changed between failed and successful attempts?

Use rounded public scenarios such as `about HK$10,000` instead of a real balance. Present the result as “我的使用记录／比较过程”, never “大家应该买”.

For troubleshooting stories, build a timeline of attempts. Treat a sequence change as evidence of correlation only; do not claim that an app-region choice, email provider, declared asset range, network setting, or bundled product caused success unless an official source confirms it.

### 2. Research every unstable fact

Browse current official sources before writing about fees, thresholds, eligibility, board lots, fund charges, interest rates, tax, app menus, or platform limits. Prefer the provider's product page and terms, exchange documents, and issuer factsheets over blogs or search snippets.

Record the page title, URL, effective date if shown, and verification date. Resolve conflicts in favor of the most specific current official document and disclose unresolved ambiguity.

Label each important statement as one of: `official rule`, `user-observed result`, `third-party experience`, or `hypothesis`. Convert unsupported causal language into precise first-person wording such as “我这次使用 Gmail 后提交成功”, not “QQ 邮箱会被拒”. Keep the date of the user's experience separate from the source-verification date.

Read [research-and-costing.md](references/research-and-costing.md) for the source hierarchy, formulas, and break-even method.

### 3. Build comparable cost scenarios

Compare like with like over the same holding period. At minimum, calculate:

`visible annual cost = fixed annual platform/account cost + capital × product ongoing-charge rate`

Apply tiered fees piecewise and distinguish average holding value from account cash balance. When useful, include rounded scenarios near `10k`, `20k`, `50k`, `100k`, and `200k` in the relevant currency.

State what is excluded: spreads, FX, taxes, levies, tracking difference, incomplete holding periods, promotions, and market returns. Describe a crossover as a mathematical fee threshold under stated assumptions, not as a buy signal.

### 4. Choose the story before choosing the visuals

Use the arc that matches the story. For a decision or cost comparison, default to:

1. Situation and plain-language conclusion
2. Money buckets or decision questions
3. App or operating steps
4. Product actually chosen and why
5. Alternatives considered and why not yet
6. Comparable annual-cost table and thresholds
7. What happens to the uninvested money
8. Official references, verification date, and disclaimer

For an account-opening or process story, default to:

1. Situation, date, and compact process map
2. Prerequisites and documents
3. Where to start and which account route was used
4. Form choices and identity verification
5. Address, delivery, and any selections that affect later steps
6. Problems encountered, what changed, and what remains only a hypothesis
7. Card receipt, activation, official product names, and post-opening setup
8. Official references, experience references, verification date, and disclaimer

For a failure self-check, organize the middle pages by independently checkable variables and end with the successful configuration without presenting it as a guaranteed fix.

Keep one main point per page. Put precise links on the last page rather than pretending Xiaohongshu supports file attachments. If page 1 has unused space, add a concise process map or conclusion rather than decorative filler.

### 5. Write for Xiaohongshu

Create:

- one plain, specific title plus two backups;
- a first-person body organized as `图1｜...` through the last page;
- 4–7 relevant hashtags;
- a one-sentence personal-record disclaimer;
- an AI-assistance disclosure when AI created or materially edited the cards.

Verify the current title/body limits in the publishing UI. If that is unavailable, keep the title comfortably short and target a body well below the apparent limit so links, tags, and disclaimers fit. Remove repeated product descriptions before removing assumptions or risk warnings.

Count the exact final text as pasted, including line breaks, hashtags, and disclosures. Prefer a shorter, plain title that states the scenario over a clever or exaggerated title.

### 6. Protect privacy before producing cards

Never expose exact balances, exact trade amounts, names, account numbers, investment IDs, order numbers, QR codes, barcodes, device identifiers, notification text, or transaction timestamps. Do not bundle the user's screenshots or local paths into a public skill or repository.

Use generic UI diagrams when screenshots add little. If real screenshots are essential, create a redaction checklist and require a final visual inspection after export.

### 7. Produce and inspect the cards

Default to a calm editorial hand-drawn style with restrained decoration, strong hierarchy, and mobile-readable type. Prefer editable HTML, slides, or design files when the user expects iteration; export portrait PNGs for publishing. Use generated illustrations for atmosphere, but render all exact Chinese text, numbers, URLs, and product codes with deterministic layout tools.

Lock the visual system on page 1 before producing the full set when style is still unsettled. Then iterate page by page: render, inspect at phone scale, inspect reported crops, fix layout, and only then treat the page as approved. Preserve the approved type scale, spacing, palette, frame geometry, and page-number position across later pages.

Use official product imagery when the exact appearance matters. Record the official page URL, name it with the formal product name, distinguish community nicknames from official names, and label any visible sample name, card number, or date as provider-supplied demonstration data. Do not fabricate a branded card or imply that an unofficial nickname is the product name.

Inspect every exported page at full-page scale and in close crops. Fix clipped text, off-center numbers, inconsistent title sizes, decorative fonts on English or digits, sparse lower areas, excessive ornaments, weak contrast, and frames that do not contain their text.

Read [cards-copy-and-privacy.md](references/cards-copy-and-privacy.md) for the page template, visual QA, redaction checklist, and publishing settings.

### 8. Run the final editorial check

Confirm all of the following before handoff:

- Every current fee or rule has a direct official source.
- Every troubleshooting claim is clearly labeled as an official rule, observed result, experience reference, or hypothesis.
- Calculations use one holding period and disclose exclusions.
- The conclusion matches the person's constraints rather than claiming universal superiority.
- No real personal balance or account identifier appears in text, images, metadata, filenames, or editable sources.
- The body fits the current platform limit with room for hashtags.
- The final reference card contains readable page titles and URLs.
- Official product names and community nicknames are not conflated.
- Every text frame passes visual containment and centering checks at phone scale.
- The post includes risk language and an AI label when applicable.
- The image order, filenames, and `图N` body sections match.

## Deliverables

Return the smallest useful complete package:

1. conclusion and break-even table;
2. three titles;
3. publish-ready body and hashtags;
4. page-by-page card copy;
5. final portrait images when requested;
6. editable source when requested;
7. privacy-redaction checklist;
8. official-source list with verification date.

When producing files, also include a simple editable source, ordered final images, the publish-ready copy, and a compact source note in one clearly named package. Do not publish user screenshots, downloaded session URLs, or private source material with the skill.

Do not claim that visible fees determine total return. Do not guarantee gains, minimize risk, or present the post as individualized financial advice.

