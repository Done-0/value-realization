# Worked example: running the four dimensions end to end

This is one full pass of the framework on a single object, to show the shape the analysis should take — stance calibration, the four-dimension flow (why it matters / current state / named real-product comparison / symbols in the heading / sharp questions), and a round-close that hands the conversation to the next round. Read `scoring-rubric.md` first for how the direction and solidity symbols are graded.

The object here is illustrative and analyzed from the idea alone — no research was run, so every market and accuracy claim is marked to-be-verified and no dimension can earn more than thin solidity (with the unmeasured veto sitting at empty). Note the grades don't track direction: two dimensions point 🟢 yet one of the 🟢s is thin and the decisive 🔴-adjacent risk hides under a green light — direction and solidity are separate axes, and this example is built to show them coming apart. Don't copy the grades; copy the moves.

---

**Object analyzed**: an AI assistant that connects to a company's internal docs, wiki, chat history, and meeting notes; an employee asks a question in natural language and gets a direct answer with links to the sources.

## Stance calibration (before the dimensions)

**Start from the concrete.** Assume this is an idea plus maybe a rough prototype — no real usage logs, no on-target interviews. So there's little concrete to reason back from; most of what follows is hypothesis, and solidity stays low. I'll say so rather than dress inference up as fact.

**Is there a target?** Only roughly. "Employees waste time hunting for information" names a direction, not a configuration — who, stuck on what, in what moment. And there's a split hiding in plain sight: whoever greenlights and pays for this (an exec, IT) is almost never whoever types questions into it (an employee mid-task). Those are two different value relationships, and the pitch quietly treats them as one. Hold that — it's the load-bearing crack. This pass runs primarily for the employee (the end user), and flags the exec (the buyer) side per-dimension where the two diverge; a real analysis would run the exec side as its own separate pass.

## Four-dimension overview

| Dimension | Direction | Solidity |
|------|:----:|:------:|
| Value Scenario | 🟡 | 🟧 |
| Value Conditions | 🟡 | 🟥 |
| Value Timeline | 🟢 | 🟧 |
| Value Delivery | 🟢 | 🟧 |

Read the shape, but don't read it as "bad direction = bad solidity." Value Conditions is 🟡: on direction, the value can hold *if* the preconditions are met — yet its solidity is 🟥 empty, not thin, because the veto (is the knowledge written down, is it current) has never been measured at all: a blind spot, not a weak inference. Look down at Value Delivery and it's 🟢 sitting on 🟧 thin: direction green, solidity slim. One 🟡 pressed onto empty, one 🟢 pressed onto thin — direction and solidity are each moving on their own, exactly as they should. Delivery's green is the one to watch above all: it's precisely the kind that manufactures confidence the foundation hasn't earned.

---

### 1. Value Scenario 🟡 🟧

**Why this dimension is critical.** It's the center of gravity — if you can't say who, in what state, gets what result, the other three have nothing to attach to. And here a specific crack is baked in: the thing is pitched as org-wide productivity, but value is produced one employee-question at a time, and those are two different relationships measured in two different ways.

**Current state.** The most plausible configuration: a newer employee or a cross-functional IC, mid-task, needs one answer that's scattered across five systems, and doesn't want to interrupt a senior colleague to get it. That's a real state and a real ache. Two problems. First, precision: "all employees" is a category, not a configuration — a two-week new hire (knows nothing, needs orientation) and a three-year veteran (knows where things are, needs the one obscure detail) want opposite things from the same box. Second, the value-relationship position is split across two parties: the employee's value is "got my answer without bugging anyone" (they achieve their own result through the product); the exec's value is "less time burned, fewer repeat questions to senior staff" (a result confirmed by an org-level metric). The tension here is that a delighted employee and a moved exec-metric are not the same event — and the pitch sells the second while the product can only directly produce the first. Why this grade: direction is 🟡 because the value can hold once you pick a side and configure for it, but solidity is 🟧 thin, because the whole read rests on an assumed configuration — no real usage or interview has told us which side, which employee, which moment actually holds.

**Named comparison.** The sharpest mirror is **Glean**, which does almost exactly this workflow, and whose value proposition is unambiguously the employee's — find what you need across all your apps. Contrast **Guru**, which makes the opposite bet: instead of retrieving across everything, it serves human-curated, verified answer cards — its value rests on trust-through-curation, not retrieval breadth. Contrast **Notion AI**, whose precondition is that the knowledge already lives in Notion — it holds only under single-source consolidation, which this product explicitly does not assume. Restore each one's precondition and the current object's own bet gets sharper: it's betting retrieval breadth beats curation, across scattered sources, with no single home.

**Sharp questions.**
1. When you say "saves the company time," whose stopwatch — the employee's five minutes, or the exec's quarterly number — and have you actually talked to the second person, or only imagined them?
2. Name the first role you'll serve: the two-week new hire or the three-year veteran. They need opposite things, and a box built for both serves neither.
3. If the answer is wrong one time in ten, how many wrong answers before the employee quietly goes back to asking a human — and is that number 3, or 1?

---

### 2. Value Conditions 🟡 🟥

**Why this dimension is critical.** This dimension carries the veto. The entire product rests on one precondition: the knowledge the employee needs is actually written down, findable, and current. If it lives in three senior people's heads, or in docs nobody has updated since the last reorg, the assistant doesn't fail loudly — it retrieves a confident, well-formatted, wrong answer.

**Current state.** The preconditions the value depends on: P1 — the knowledge exists in text, not just in people's heads; P2 — it's current (a stale doc becomes a confident wrong answer); P3 — the permission model doesn't fracture retrieval into uselessness; P4 — employees will trust a machine answer enough to act instead of pinging a colleague. Condition-with-time is brutal here: the day it launches, the assistant freezes a snapshot of the company's doc quality, but docs rot, teams reorg, and nobody is paid to maintain knowledge for the bot. The tension here is the cruel irony — the tool's value is highest exactly in companies whose knowledge is messiest and most scattered, which is precisely where the knowledge is least written-down and least current, so retrieval quality is worst where the need is greatest. Why this grade: direction is 🟡 because the value can hold *if* the preconditions are met, but solidity is 🟥 empty, not merely thin — P1 and P2 are the veto and neither has been measured at all, so this is a blind spot, not a weak inference. Note this is a 🟡 sitting on empty while Delivery below is a 🟢 sitting on thin: direction and solidity are moving independently, exactly as they should.

**Named comparison.** **Stack Overflow for Teams** bets on the same precondition (knowledge written down) but makes the writing-down the product itself — it manufactures the condition instead of assuming it. **Guru** attacks P2 head-on with human verification and expiry dates on answer cards — an explicit freshness mechanism this product lacks. Holding both up: the current object has quietly assumed the two hardest preconditions (written-down, current) are someone else's problem.

**Sharp questions.**
1. What fraction of the answers your users actually need exist in writing today, versus in three senior people's heads — and if you don't know, why wasn't that the very first thing you measured?
2. When a doc is eight months stale, does the assistant say "I'm not sure this is still current," or answer with full confidence — and which one did you build first?
3. After launch, who maintains the knowledge so the bot stays right, and what is their incentive when it's explicitly not their job?

---

### 3. Value Timeline 🟢 🟧

**Why this dimension is critical.** The "hunting for an answer" pain is acute and in-the-moment — the value has to arrive in seconds, mid-task, or it's worthless. A timeline mismatch would be fatal; a match is a genuine edge.

**Current state.** The delivered value is immediate: ask, get a cited answer, keep working. That matches the scenario and the user's expectation exactly — a real strength. But there's a second clock. The org-level payoff the exec was sold — less wasted time, fewer interruptions to senior staff — only appears in aggregate over months, and in practice almost never gets measured back to the tool. The tension here is that user value is instant and visible while buyer value is slow and rarely verified, so the product can feel useful to every employee while the exec quietly wonders, at renewal, where the ROI actually went. Why this grade: direction is 🟢 — immediacy genuinely fits an acute pain — but solidity is 🟧 thin, because that the second clock never gets measured is an unverified claim about buyer behavior, not something observed here.

**Named comparison.** **Slack AI** and **Microsoft Copilot** share this instant-answer timeline embedded where work already happens — the match is real and well-precedented. The reverse contrast is **Duolingo**, whose users knowingly commit to a long journey and tolerate delay; here delay is intolerable and the product correctly delivers immediacy. On timeline-fit alone, this object is well-placed.

**Sharp questions.**
1. The employee gets value in five seconds; the exec gets a number in six months that nobody is tracking — at renewal, which of those two clocks decides whether the contract survives?
2. If usage is high but "time saved" stays unmeasurable, is that a healthy product or just a subscription nobody dares to cancel?

---

### 4. Value Delivery 🟢 🟧

**Why this dimension is critical.** The user receives only what they can perceive. A direct answer plus clickable source links is one of the most concrete, low-loss carriers imaginable — a genuine asset. It is also, on this specific product, the trap.

**Current state.** Delivery is arguably the strongest dimension: a plain answer with sources the user can open is concrete, pointable, and instantly graspable. The tension here is that delivery is *too* good relative to correctness — a citation makes the answer *look* verified even when retrieval pulled the wrong or stale document, and polish outruns accuracy. A cited-but-wrong answer is more dangerous than an obviously-uncertain one, because the citation is exactly what makes the user stop checking. This is where the pretty fog lives: green because it's vivid, dangerous because the vividness is doing the job that verification should. Why this grade: this is the textbook 🟢 🟧 — direction green because the carrier is genuinely low-loss, solidity thin because "vivid delivery helps rather than misleads here" is pure assumption, and on the evidence of the Conditions dimension a contestable one. 🟢 on thin is the pretty fog the rubric warns about; it is not the same as a 🟢 that has earned its solidity.

**Named comparison.** **Perplexity** uses the same citation-first delivery, and it works partly because a wrong consumer-search answer is low-stakes; an employee acting on a wrong internal-policy answer is not. Same delivery form, different stakes. **Grammarly** is the cautionary contrast: its output is verifiable at the moment of delivery — you see the corrected sentence and know it's right — whereas this product's answer is not verifiable at delivery unless the user opens the source, which most won't. It borrows Grammarly's concreteness without Grammarly's verifiability.

**Sharp questions.**
1. When the assistant cites a source, what fraction of users actually click through versus trust the summary — and if most trust the summary, is the citation doing verification or just manufacturing confidence?
2. Would you show "based on a document last edited eight months ago" as prominently as the answer itself — and if not, whose interest does burying it serve?

---

## Round close (the start of the next round, not a wrap-up)

**Current four-dimension state.**
- **Value Conditions 🟡 🟥 — the decisive foundation, and a total blind spot.** Whether the needed knowledge exists in writing and current (P1 + P2) is the veto, and it sits at empty — not measured at all. Nothing downstream matters until it is. This is where the product is either real or a confident-wrong-answer machine.
- **Value Scenario 🟡 🟧 — the muddled center.** Two value relationships (employee vs exec) are being sold as one and measured differently. Pick which you serve first, honestly.
- **Value Delivery 🟢 🟧 — the pretty fog.** A green light on thin solidity: cited answers look verified whether or not they are, so the vividness outruns the correctness. This is the exact combination the rubric flags as most dangerous — watch it.
- **Value Timeline 🟢 🟧 — the genuine edge, still unverified.** Instant answers match an acute pain — the least of your worries, except for the hidden second clock on the exec's side, which is why even this one is thin, not solid.

**The one question to attack first (veto power, falsifiable, executable).** Before building anything more, measure retrieval quality on a real slice: pull 50 questions employees actually asked last month (from help-desk tickets or chat logs), and for each, check whether a correct, current answer already exists somewhere the assistant could retrieve. If that number is low, the product's ceiling is set by your documentation, not your model — and the first real work is knowledge-capture, not a smarter assistant. This single measurement gates everything above it.

**The entry to the next round (ball back to you).** Answer this before writing another line of the pitch: if the honest retrieval-quality number comes back low, do you keep selling "instant answers to any question" — and watch trust collapse on the first confident wrong answer — or do you reframe the product as "surfaces what's written and flags what isn't, so people know when they still need to ask a human"? Those are two different products, with two different buyers and two different promises. Which one are you actually building?

*(All market and accuracy claims above are marked to-be-verified — no research was run. The next step for solidity is the retrieval-quality measurement above, plus five conversations with real target employees about the last time they hunted for an internal answer: what the situation was, what they did, and whether they'd have trusted a machine's answer over a colleague's.)*
