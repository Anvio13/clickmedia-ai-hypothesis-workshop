# Landing-page structure: from segment to working page

Use this reference after Prompt 2 has selected an offer. It is the page architecture shown in the Clickmedia presentation: a landing page must supply **motivation + ability + trigger**. A block may have more than one role, but all three must be present across the page.

Do not begin implementation until every block has a sentence of final copy or an explicit, evidenced reason why it is unavailable. Do not silently replace missing proof with invented testimonials, metrics, logos, outcomes, or features.

## Input contract

Before producing the page, carry forward these named inputs:

| Input | Comes from | Why the page needs it |
|---|---|---|
| Primary segment | Prompt 1 | Determines whose context and language the page uses |
| Core Jobs and Big Job | Prompt 1 | Supplies desired progress, recognition, and outcome image |
| Selected offer | Prompt 2 | Supplies the central promise |
| Product mechanisms | Prompt 2 | Supplies truthful explanation of how it works |
| Barriers and gaps | Prompt 2 | Supplies objections and constraints; gaps must remain visible |
| Conversion action | User brief | Defines CTA text and the next step |
| Available proof/assets | User brief | Defines what can be shown rather than fabricated |

## The nine blocks

Keep this order unless the user supplies evidence for a different one. For every block, state its behavioural role: **motivation**, **ability**, **trigger**, or a combination.

| # | Block | Job on the page | Must be grounded in | Minimum output |
|---|---|---|---|---|
| 1 | **One-line essence** | Hook the audience: what this is, for whom, and why it matters | Selected segment + offer | Headline, supporting line, primary CTA, and first-screen visual direction |
| 2 | **Path to the result** | Show understandable steps to the goal | Core Job + real product mechanism | 3–5 steps; each describes an actual step, not a slogan |
| 3 | **Quick result** | Let the visitor feel an effect early | Easiest credible Micro Job | Interactive/demo/preview idea or a concrete early outcome; if none exists, say so |
| 4 | **Value** | Close each important client job | Core Jobs, Micro Jobs, and linked product mechanisms | One value statement per job, each paired with the mechanism that enables it |
| 5 | **Recognition** | Create “this is about me” | Segment context, trigger, Point A emotions, Big Job | Situations, triggers, and language the segment recognises; no generic demographic stereotypes |
| 6 | **How we do it** | Remove doubt that the product can deliver | Products & Services, Pain Relievers, Gain Creators, available proof | Explain the mechanism, process, evidence, limits, and what happens after the CTA |
| 7 | **Outcome image** | Make life after progress concrete | Big Job and desired Point B | Specific future scene, emotions, and outcomes; visual direction only where assets exist or are marked as placeholders |
| 8 | **Barriers** | Answer concrete objections | Named barriers and honest product answers | Objection → factual response. If there is no answer, preserve the gap rather than invent reassurance |
| 9 | **Alternatives** | Explain why this route is not merely another alternative | Credible current solutions/competitors and actual differentiation | Comparison by job or criterion; never make unverified claims about competitors |

## Copy-to-code handoff

Only after the nine blocks are complete, produce the implementation brief below before HTML:

```text
Page goal: [single visitor action]
Primary segment: [name]
Offer: [selected offer]
Primary CTA: [label] → [what happens next]
Proof available: [only confirmed items]
Assets available: [real files/URLs] or “placeholders only”
Mobile priorities: [first-screen CTA, reading order, form length, tap targets]
Block order: 1 → 9, with one-sentence purpose for each
```

The resulting `index.html` must:

- retain the block order and final copy;
- use one clear primary CTA consistently, with secondary actions only when they do not compete;
- use mobile-first layout and readable typography;
- label placeholders rather than presenting them as customer evidence;
- contain no fake testimonials, counters, client logos, case outcomes, or comparative claims;
- be a self-contained, runnable page when the requested environment allows it.

## Completion check

Before handing over the landing page, verify:

1. A visitor can identify the product, audience, value, and next action from Block 1.
2. Every promised value has a matching mechanism in Blocks 2, 4, or 6.
3. Every substantial barrier has either a truthful response or an explicit unresolved gap.
4. The Point B image is tied to the segment’s Big Job rather than a generic aspiration.
5. The CTA and next step are consistent on desktop and mobile.

## Source note

This structure is derived from the Clickmedia workshop presentation, slides 19–23: motivation + ability + trigger; and the nine named blocks with their purposes. It is a workflow guide, not evidence that a particular structure will increase conversion.
