# Result-analysis method: evaluate what the landing page produced

Use this after the skill has produced a visual design or a working landing page. The goal is not to judge whether the design is fashionable. The goal is to decide whether the page helps the intended visitor understand the offer, trust it, and take the intended next step.

## Required input

Do not run a full analysis without all four items:

1. **Product** — confirmed features, limitations, and offer.
2. **Target audience** — the selected segment from Prompt 1.
3. **Traffic source** — where the visitor comes from and what the ad or referral promises.
4. **Result to assess** — a design mock-up, URL, screenshot set, or working page.

If an item is absent, state what cannot be concluded. Do not fill gaps with assumed customer behaviour, conversion data, testimonials, or competitor facts.

## Six dimensions

| Dimension | Question to answer | What to inspect |
|---|---|---|
| Market | Does the page reflect how this category and audience decide? | Fresh relevant CRO cases, A/B tests, industry research, benchmarks, UX research, and customer behaviour data. Check comparability before using it. |
| First screen | Can the visitor understand the offer and next action at a glance? | Product, audience, value, message match with traffic source, CTA, visual priority, trust, and overload. |
| Page logic | Does the story answer questions in a useful order? | What it is → why for me → result → why believe → why this route → what next. Look for gaps, repetition, attention leaks, and badly placed CTAs. |
| Design and typography | Does the form help the message be read and trusted? | Hierarchy, readability, contrast, type size, line length, spacing, grid, buttons, cards, visual accents, and whitespace. |
| Mobile experience | Does mobile work as a primary experience? | First screen, reading order, tap targets, CTA, forms, cards, scroll length, horizontal layouts, and overload. If no mobile design exists, report risks rather than pretending to review it. |
| Trust and CTA | Are reasons to believe and the next action convincing? | Evidence quality: cases, reviews, data, logos, guarantees, real photos, and outcome proof. Assess credibility, not mere presence. |

## How to classify a finding

Every material finding must have exactly one label:

| Label | Use only when | Example language |
|---|---|---|
| **MARKET EVIDENCE** | There is current relevant research or a comparable case. Cite it and state limits of transfer. | “Research on a comparable B2B lead form suggests …; this page differs because …” |
| **UX EVIDENCE** | The issue is objectively observable in reading, accessibility, or interface use. | “The primary action is below competing visual elements, so it is easy to miss.” |
| **CRO HYPOTHESIS** | The change is plausible but needs traffic or an experiment to verify. | “This may reduce understanding; test the two versions after launch.” |

Never claim that a change “will increase conversion” without evidence from this specific page and test. Use “may create risk”, “may reduce understanding”, or “is worth an A/B test” when the effect is unproven.

## The decision report

Return the following, in this order:

1. **Verdict** — one 5–8 sentence paragraph: page strength, clarity for the segment, traffic-message match, trust, main constraint, and whether it is ready for implementation or traffic. End with one of: `launch`, `launch after fixes`, `do not launch yet`, plus a `X/100` assessment.
2. **What matters most** — only 3–5 findings. For each: title, what is happening, why it matters, concrete action, impact (`high`, `medium`, `low`), and evidence label.
3. **Visitor journey** — a single paragraph that follows a person from the stated traffic source through the page: what they understand, where doubt rises, where trust grows, where attention may drop, and what moves or blocks the CTA.
4. **What to change** — one compact table: `Priority | Where | What is wrong | What to do`. Use only `1 — before launch`, `2 — improve soon`, `3 — test after launch`; no more than ten changes.
5. **What already works** — 3–5 strengths that must survive revision.
6. **Owner summary** — main problem, main strength, first change, and conversion potential after fixes (`low`, `medium`, `high`). This is a directional assessment, not a conversion forecast.

## From analysis to the next iteration

Use Prompt 6 only with the existing conversation context: segment, selected offer, copy, HTML, and analysis report. Translate each approved Priority 1 or Priority 2 finding into one of these actions:

- **Copy correction** — revise the exact block while preserving confirmed product facts.
- **Layout correction** — change hierarchy, ordering, CTA placement, or mobile presentation.
- **Proof request** — mark the missing case, metric, photo, or guarantee as a user-provided dependency; never fabricate it.
- **Experiment** — retain the current page as a control and state the one hypothesis that traffic should test.
- **Strategic revisit** — return to the segment or offer only when the audit directly shows that the page cannot truthfully deliver its central promise.

After revision, output a short change log: `finding → change made → evidence label → what remains unverified`.

## Source note

This method consolidates the Clickmedia workshop’s Prompt 5 and Prompt 6, together with the presentation’s six audit areas: market, first screen, logic, design, mobile version, and trust/CTA. It is a structured review method, not a guarantee of conversion.
