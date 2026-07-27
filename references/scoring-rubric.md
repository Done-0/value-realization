# Scoring Criteria: Direction and Solidity

Every dimension is judged from two independent angles: **direction** (does value hold on this dimension) and **solidity** (how much of that judgment rests on evidence). The two must be given separately and cannot substitute for each other — a green light might mean "confirmed to hold" or merely "assumed to hold," and the difference is large.

This file is an anchor for judgment, not a formula to apply mechanically. The same signal can map to different grades across different products, markets, users, and scenarios. When you give a grade, attach one line of "why this grade" stating the basis. When a grade conflicts with the detailed analysis, the full analysis wins.

---

## Direction axis (🔴🟡🟢)

Direction answers: in the current value scenario, does this dimension hold. It describes the **conclusion** of the judgment, not how much evidence there is.

- **🟢 Holds**: on this dimension, the value relationship stands up in the current scenario; the key conditions are present.
- **🟡 Partially holds**: the direction is right, but there's an obvious gap — some conditions aren't met, or it only holds in a narrower range.
- **🔴 Doesn't hold**: on this dimension the value relationship doesn't stand up, or a decisive key condition is missing.

Note that 🔴 isn't always bad news. A clear "confirmed not to hold" conclusion is more useful than a vague "looks like it holds but lacks basis" judgment — it tells you to switch targets.

---

## Solidity axis (🟩🟨🟧🟥)

Solidity answers: how much of this judgment rests on evidence versus still hanging on assumption. The denominator is the set of premises this dimension depends on; solidity is roughly the share of those already backed by evidence. It's a **proportion**, not a good/bad verdict, so it's shown with a green-to-red color scale of squares — the greener the color, the more evidence; the redder, the more it hangs on assumption.

- **🟩 Solid**: the judgment is basically evidence-backed — on-target user interviews, behavioral data, real usage records, comparable cases — the key preconditions are all verified and the boundaries are drawn.
- **🟨 Half**: evidence and assumption in equal measure. Part verified, part still inferred. The most common state in real projects.
- **🟧 Thin**: a direction can be given, but most of the basis still hangs on assumption, unsupported by on-target evidence.
- **🟥 Empty**: not yet explored, a blind spot, with no basis to speak of.

The color of the square draws the proportion itself: 🟩 solid, 🟨 half, 🟧 thin, 🟥 empty. It uses squares while the direction axis uses round lights (🔴🟡🟢) — two different visual families. Shape plus color together let you tell at a glance which is "does it hold" and which is "how much rests on evidence," without confusing the two sets of symbols.

Don't report fake precision like "63%." Solidity is itself an estimate; four grades plus one line of basis is enough. Its job is to make "where it's fuzzy, and how fuzzy" visible, not to look precise.

**The "thin" and "empty" grades of solidity are exactly the checklist of what to go talk about and verify next.**

---

## How direction and solidity combine

Direction and solidity are orthogonal; any combination can occur, and that's what fits reality:

- **🟢 🟩**: holds, with evidence. You can act on it.
- **🟢 🟧**: looks like it holds, but mostly on assumption — the most dangerous "pretty fog." The first thing to go verify.
- **🟡 🟨**: partially holds, evidence and assumption mixed — most common in real projects. Mark the gaps and the to-be-verified items.
- **🔴 🟩**: confirmed not to hold, with evidence. A valuable conclusion — switch targets or change direction.
- **🔴 🟧**: looks like it doesn't hold, but the basis is thin; don't rush to reject it, it may just be unexplored.
- **Any direction 🟥**: this dimension hasn't really been analyzed yet; fill in the basis first, don't rush to give a direction.

---

## How to present

- **Give a four-dimension overview up front.** As the analysis opens, use one small table to list all four dimensions' direction and solidity at once, so the reader sees the whole picture at a glance — which dimension is solid, which is empty, where the "pretty fog" is. This is navigation for the reader: transmit the whole low-loss first, then expand each dimension in detail.

  | Dimension | Direction | Solidity |
  |------|:----:|:------:|
  | Value Scenario | 🟢 | 🟩 |
  | Value Conditions | 🔴 | 🟥 |
  | Value Timeline | 🟡 | 🟨 |
  | Value Delivery | 🟢 | 🟧 |

- **The overview doesn't replace reasoning.** The overview is only navigation, not the conclusion itself. Each dimension still has to expand into full reasoning below, then land back on direction and solidity — you can't treat the symbols up front as "already analyzed." Within each dimension the order is always reasoning first, symbols after.
- **Symbols go straight into the dimension heading, direction first, solidity right after.** Each dimension's direction light and solidity square follow the heading, the two next to each other, e.g. `### 3. Value Timeline 🟡 🟨` or `### 2. Value Conditions 🔴 🟧`. Written adjacent, a `🟢 🟧` "pretty fog" jumps out at a glance; split apart, you'd miss it.
- **Reasoning goes into the body, not a standalone label line.** "Why this grade" shouldn't be a separate line after the heading; work it into the dimension's reasoning — with phrases like "the current state is…" "the tension here is…" that state the judgment fully. Symbols only make the state scannable; the basis for the judgment always lives in the reasoning text.

---

## Per-dimension reference

Below is what the three direction grades typically look like for each dimension. The solidity axis is common across all four (how much of the basis rests on on-target evidence), so it isn't repeated per dimension.

### Value Scenario

Looks at: whether you can lock in a precise-enough value-relationship configuration — who, in what state, in what situation and conditions, getting what result; and whether the value-relationship position is stated clearly.

- **🟢**: the configuration is precise — the segment, state, and the problem they're stuck on are all pinned down, and the value-relationship position is clear (whether an external object is confirmed valuable, the user achieves their own result, or the user is confirmed valuable through feedback).
- **🟡**: there's a rough scenario, but not precise enough — only a broad segment is circled, or the relationship position is vague, treating "can be used" as "produces value."
- **🔴**: you can't say which configuration value is produced in, or pushing on it reveals there's no target at all. Here the direction itself is an important conclusion; the next step is to set a target or go talk.

### Value Conditions

Looks at: on what basis value holds, whether the preconditions supporting it are still present or will fail as time and the market shift; whether borrowed experience has been abstracted to a transferable second-layer condition.

- **🟢**: the key preconditions are all present and still hold after the test of time; borrowed experience has had its conditions restored and second layer extracted, confirmed satisfied now.
- **🟡**: some conditions present, some changed or in doubt; or a case was borrowed but only half its conditions match.
- **🔴**: a decisive condition no longer holds, or has drifted out of validity over time, yet the judgment still runs on the old conditions.

### Value Timeline

Looks at: whether value is immediate or delayed, whether both sides know it's coming, what sustains investment during the wait, and whether the timeline matches the product's nature and user expectations.

- **🟢**: the timeline matches the product's nature, the scenario, and user expectations; if delayed, the user knows value is coming and there's perceptible progress during the wait.
- **🟡**: the timeline is broadly reasonable but shows signs of mismatch — e.g. delayed value with no perceptible progress during the wait, or short-term touchpoints starting to override the long-term goal.
- **🔴**: the timeline conflicts with the product's nature or user expectations — immediate value forced into a long-term mechanism, or long-term value that loses users before they see a result.

### Value Delivery

Looks at: whether the value already produced can be perceived, understood, and verified low-loss by the target side, or is buried in the backend and can't get out.

- **🟢**: the user can point at something concrete and say "I got this"; value has a low-loss, perceptible, showable carrier.
- **🟡**: value is partly perceptible but still with obvious loss — the user has to infer it themselves, or only part of it is seen.
- **🔴**: value is buried in backend logic; the user can't perceive it at all. Invisible value feels like no value.
