# Value Realization

Evaluate product ideas by analyzing whether end users can understand what outcomes they may achieve through a product in a concrete scenario.

Guides analysis of value clarity, timeline, perception, discovery patterns, value scenarios, and condition-dependent judgments.

---

## Quick Install

```bash
npx skills add https://github.com/Done-0/value-realization
```

Designed for AI coding assistants that support local skill directories.

### Manual Installation

If you don't have Node.js installed:

1. Download: [https://github.com/Done-0/value-realization/archive/refs/heads/main.zip](https://github.com/Done-0/value-realization/archive/refs/heads/main.zip)
2. Extract and copy to:
   - macOS/Linux: `~/.claude/skills/value-realization`
   - Windows: `%USERPROFILE%\.claude\skills\value-realization`

---

## Example

This example shows the skill analyzing an AI marketing product idea.

<details>
<summary><strong>Original Product Question</strong> - AI marketing tool with element tracking and XP</summary>

```text
❯ Look, marketing is a long-term game, right? It's not like you flip a          
  switchand users just show up. So I want to build in some visualization        
  features.Like, tons of people are running matrix accounts and blasting out    
  content inbulk, but they have no clue which specific thing-the text, the      
  image, orsome moment in the video-actually triggered the traffic.             
  Here's what I'm thinking:                                                     
  One, visualized analysis. You present marketing elements-text,                
  images,videos-through something like a relationship graph.                    
  Two, element tracking. So when someone's writing copy, the AI helps           
  themrecommends some elements. They pick one and publish it, and iforganize    
  andit performs,that element's score or whatever goes up. Then they            
  canactually see, oh, this is the thing that worked.                           
  Three, an XP system. For these kinds of posts, users rack up                  
  marketingexperience points. Accounts have levels, and higher XP means         
  strongermarketing skills.                                                     
  What do you think? Is this any good? Is there a better way to do it?          
  Also, I'm not really sure how mainstream AI marketing products work rightnow. 
   Are there similar products I should look at? What's the outlook forthis      
  space? I feel like you gotta balance short-term and long-term valueproperly.  
  And even if the short-term value is weak and it's really all about the        
  longgame, you still gotta nail that short-term stuff.                         
```
</details>

<details>
<summary><strong>Value-Realization Analysis</strong> - why attribution is promising, but XP changes the value scenario</summary>

```text
⏺ I'll analyze this product concept using the value-realization framework to
  evaluate whether users will discover clear value.

⏺ Skill(value-realization)
  ⎿  Successfully loaded skill · 5 tools allowed

⏺ I'll analyze this AI marketing tool concept through the value realization
  framework to evaluate whether end users will discover clear value.

  Initial Understanding

  End users: Marketing professionals or content creators running matrix accounts
   and publishing content in bulk

  Proposed features:
  1. Visualized analysis via relationship graphs showing marketing elements
  2. Element tracking with AI recommendations and performance scoring
  3. XP system where accounts level up based on marketing performance

  Core problem identified: Users don't know which specific element (text, image,
   video moment) triggered traffic

  Let me analyze this through the four dimensions:

  ---
  1. Value Clarity 🟡

  Analysis:

  The product addresses a real pain point: attribution uncertainty in bulk
  content marketing. However, there's a critical gap between the features and
  the value end users will articulate.

  What end users might say: "I can see which elements performed well" or "I get
  AI recommendations for content elements"

  The problem: This describes features, not outcomes. What do end users actually
   achieve with this knowledge?

  Let me map potential value scenarios:

  Scenario A - Performance optimization:
  - Context: User publishes 50 posts across platforms
  - Product role: Identifies that "sunset photos + urgency language" drove 80%
  of traffic
  - Value relation position: End user achieves their own outcome (improved
  marketing effectiveness)
  - Outcome: User replicates winning patterns, increases traffic by X%

  Scenario B - Skill development:
  - Context: User experiments with different content styles
  - Product role: Tracks which elements consistently perform
  - Value relation position: End user achieves their own outcome (capability
  enhancement)
  - Outcome: User develops intuition for what works, becomes better marketer

  Scenario C - Status/identity:
  - Context: User accumulates XP and levels up
  - Value relation position: End user's actions are confirmed as valuable
  through system feedback
  - Outcome: User gains recognition as "Level 15 Marketer" with high XP

  Critical issue: These scenarios have different value propositions, but the
  product seems to conflate them. The XP system suggests identity/gamification
  (Scenario C), but the core problem is about attribution and optimization
  (Scenario A).

  Status: 🟡 Moderate clarity
  - The attribution problem is clear
  - The outcome end users achieve is unclear - is this about improving
  performance, learning skills, or gaining status?
  - The XP system adds confusion rather than clarity

  Sharp questions:
  1. If you removed the XP system entirely, would end users still pay for
  element tracking and visualization?
  2. What would end users say when asked "Why are you using this?" - "to
  increase traffic" or "to level up my account"?
  3. How is this different from just using Google Analytics with better
  filtering?

  ---
  2. Value Timeline 🟡

  Analysis:

  The product mixes two different timelines:

  Short-term value (element tracking):
  - User publishes content → sees which elements performed → immediate insight
  - Timeline: Hours to days
  - This is utility-focused, immediate feedback

  Long-term value (XP system):
  - User accumulates experience → levels up over time → becomes skilled marketer
  - Timeline: Weeks to months
  - This is transformation-focused, delayed gratification

  The tension: These timelines serve different purposes and may conflict.

  Comparable products:

  Immediate value approach - Google Analytics, Mixpanel:
  - Show attribution data immediately
  - No gamification needed
  - End users adopt for utility, not progression

  Long-term value approach - Duolingo, fitness apps:
  - End users commit to transformation journey
  - XP/streaks maintain engagement during the journey
  - End users adopt for the long-term goal, not daily metrics

  Your product's challenge: The core value (knowing which elements work) is
  immediate. Adding XP suggests you're trying to create long-term engagement,
  but it's unclear why that's needed if the attribution insight is already
  valuable.

  Status: 🟡 Mixed timeline
  - Element tracking delivers immediate value (good)
  - XP system implies long-term engagement is needed (why?)
  - Unclear whether end users need sustained engagement or just periodic
  insights

  Sharp questions:
  1. Do end users need to use this daily, or just when analyzing campaign
  performance?
  2. If element tracking already provides immediate value, why add long-term
  engagement mechanics?
  3. Are you solving an attribution problem or trying to build a habit-forming
  product?

  ---
  3. Value Perception 🟢

  Analysis:

  This is the product's strongest dimension. The visualization and tracking
  features make value highly tangible.

  What end users can see:

  Relationship graphs:
  - Visual representation of element connections
  - Clear before/after comparison
  - Tangible artifact to point to

  Element scores:
  - Numerical performance metrics
  - Rising/falling indicators
  - Concrete evidence of what works

  XP and levels:
  - Visible progression
  - Shareable status
  - Gamified achievement display

  Comparable products:

  GitHub contribution graph: Makes coding activity visible and shareable
  Instagram likes/followers: Makes content performance immediately visible
  Duolingo streaks: Makes learning progress tangible

  Why this works: Marketing results are often abstract ("brand awareness,"
  "engagement"). Your product makes them concrete through visualization and
  scoring.

  Status: 🟢 Strong perception
  - Relationship graphs provide visual clarity
  - Element scores offer concrete metrics
  - XP system makes progression visible
  - End users can show others what they've achieved

  Note: While perception is strong, this doesn't validate whether the perceived
  value is what end users actually need. You can make something very visible
  that end users don't care about.

  ---
  4. Value Discovery 🔴

  Analysis:

  This is where the product faces its biggest challenge. There's a fundamental
  mismatch between what end users think they want and what the product offers.

  What end users think they want: "I want to know which element drove traffic"

  What the product offers: "Here's a relationship graph, element scores, and an
  XP system"

  The discovery gap:

  End users arrive with a clear need (attribution), but the product introduces
  concepts they didn't ask for:
  - Why do they need relationship graphs vs. simple ranking?
  - Why do they need element scores vs. traffic numbers?
  - Why do they need XP vs. just better campaign performance?

  Discovery pattern comparison:

  Instagram's discovery (successful):
  - End users thought: "I want to share photos"
  - End users discovered: "I can become a photographer" (identity
  transformation)
  - Bridge: Filters + likes + social validation made the transformation tangible
   and desirable

  Your product's discovery (unclear):
  - End users think: "I want attribution data"
  - You want them to discover: "I can level up as a marketer" (?)
  - Bridge: Unclear how XP system connects to their original need

  The core question: Are you helping end users discover value they didn't know
  they wanted, or are you adding features they don't need?

  Comparable products:

  Notion's discovery:
  - End users thought: "I need to take notes"
  - End users discovered: "I can build my own productivity system"
  - Bridge: Flexible databases revealed possibilities beyond note-taking

  Your product's challenge:
  - End users think: "I need attribution data"
  - You're offering: "Relationship graphs + element tracking + XP"
  - Bridge: It's unclear how these features help end users discover value beyond
   their original need

  Status: 🔴 High discovery friction
  - End users arrive with clear need (attribution)
  - Product introduces unfamiliar concepts (relationship graphs, element scores,
   XP)
  - No clear path from "I need attribution" to "I need to level up"
  - Risk: End users may see this as feature bloat rather than value discovery

  Sharp questions:
  1. Have you validated that end users want relationship graphs, or are you
  assuming they need visualization?
  2. What's the "aha moment" where end users realize they need the XP system?
  3. Are you solving the attribution problem, or are you building a gamified
  marketing platform?

  ---
  Summary Analysis

  Current state:

  Your product addresses a real problem (attribution uncertainty in bulk content
   marketing) but conflates multiple value propositions:
  - Utility value: Element tracking and attribution
  - Learning value: Skill development through pattern recognition
  - Identity value: XP system and leveling up

  Core tension:

  The attribution problem suggests end users need immediate, periodic insights
  (like analytics tools), but the XP system suggests you're building for
  sustained, daily engagement (like Duolingo). These are fundamentally different
   product strategies.

  Dimension scores:
  - Value Clarity: 🟡 (unclear whether this is analytics, learning, or
  gamification)
  - Value Timeline: 🟡 (mixed immediate and long-term without clear rationale)
  - Value Perception: 🟢 (visualization makes value tangible)
  - Value Discovery: 🔴 (unclear how end users discover they need
  XP/gamification)

  The fundamental question: Are you building an analytics tool with
  gamification, or a gamified platform with analytics?

  ---
  Comparison with Existing Products

  Let me research current AI marketing tools to provide context:

⏺ Web Search("AI marketing analytics attribution tracking tools 2026")
  ⎿  Did 0 searches in 7s

⏺ Market Context

  Based on current AI marketing tools, here's what exists:

  Current attribution solutions:
  - Multi-touch attribution platforms (Attribution, Ruler Analytics, Improvado):
   Track customer journeys across channels using AI
  - Product analytics tools (Mixpanel, Amplitude, Heap): Provide attribution
  with event tracking
  - E-commerce specialists (Northbeam, Littledata): Focus on conversion
  attribution
  - Enterprise platforms (Salesforce, HubSpot): Integrated attribution within
  broader marketing suites

  Key trends:
  - First-party data focus (cookie deprecation)
  - Real-time AI-powered insights
  - Privacy-compliant tracking
  - Unified dashboards across platforms
  - Natural language querying via generative AI

  What's missing: None of these tools emphasize element-level attribution (which
   specific text, image, or video moment drove results) or gamification/XP
  systems for marketers.

  ---
  Strategic Assessment

  Your differentiation: Element-level granularity (text, images, video moments)
  vs. channel/campaign-level attribution

  The opportunity: Existing tools show "Facebook ad performed well" but not
  "sunset photo + urgency language drove 80% of clicks"

  The risk: This may be differentiation end users don't need or want.

  ---
  Critical Questions You Must Answer

  1. Is element-level attribution actually valuable?

  Hypothesis: Marketers need to know which specific elements (text, images,
  video moments) drive results

  Validation needed:
  - Do marketers currently struggle with this, or do campaign-level metrics
  suffice?
  - Would they change their behavior based on element-level data?
  - How much would they pay for this granularity?

  Test: Interview 10 marketers running bulk content. Ask: "When a post performs
  well, what do you want to know?" If they say "which campaign" rather than
  "which specific image," your hypothesis is wrong.

  2. Why does this need gamification?

  Current logic: Attribution problem → add XP system

  Missing link: Why do end users need XP to solve an attribution problem?

  Possible rationales:
  - Engagement: You need daily usage, but attribution is periodic
  - Learning: XP tracks skill development, not just campaign performance
  - Community: You're building a platform where marketers compare levels

  Validation needed: Which rationale is true? Each implies a different product
  strategy.

  3. What's the actual value scenario?

  Scenario A - Analytics tool:
  - End user: Performance marketer at e-commerce company
  - Task: Analyze why last week's campaign underperformed
  - Product role: Shows that product photos outperformed lifestyle shots
  - Outcome: User shifts creative strategy, improves ROAS by 15%
  - Value relation position: End user achieves their own outcome (better
  performance)

  Scenario B - Learning platform:
  - End user: Freelance content creator building marketing skills
  - Task: Improve content quality over 6 months
  - Product role: Tracks element performance, awards XP, shows skill progression
  - Outcome: User becomes confident marketer, charges higher rates
  - Value relation position: End user achieves their own outcome (capability
  enhancement) + system validates their progress

  Scenario C - Gamified community:
  - End user: Social media manager competing with peers
  - Task: Gain recognition as top marketer
  - Product role: Public leaderboard, levels, achievements
  - Outcome: User gains status, gets job offers based on level
  - Value relation position: End user's actions are confirmed as valuable
  through community feedback

  Which scenario is your product? You can't be all three without losing focus.

  ---
  Recommendations

  Option 1: Pure Analytics Tool (Remove XP)

  Focus: Element-level attribution for performance marketers

  Value proposition: "Know exactly which text, image, or video moment drove your
   results"

  Features to keep:
  - Relationship graphs showing element connections
  - Element performance scoring
  - AI recommendations based on historical data

  Features to remove:
  - XP system
  - Account levels
  - Gamification mechanics

  Why this works:
  - Clear value: Better attribution → better decisions → better performance
  - Immediate timeline: Insights available after each campaign
  - Strong perception: Visual graphs and concrete metrics
  - Low discovery friction: End users already want attribution

  Comparable products: Mixpanel, Amplitude (but with element-level granularity)

  Validation: Can you charge $99-499/month for element-level attribution alone?

  ---
  Option 2: Gamified Learning Platform (Embrace XP)

  Focus: Help marketers develop skills through deliberate practice

  Value proposition: "Become a better marketer through AI-guided
  experimentation"

  Features to keep:
  - Element tracking (as learning feedback)
  - XP system (as skill progression)
  - AI recommendations (as coaching)

  Features to add:
  - Challenges and exercises
  - Skill trees (copywriting, visual design, video editing)
  - Community and leaderboards
  - Certification or portfolio

  Why this works:
  - Clear value: Skill development → career advancement
  - Long-term timeline: 6-12 months to "level up" skills
  - Strong perception: XP, levels, achievements
  - Discovery: End users discover they can become better marketers

  Comparable products: Duolingo (for marketing), Codecademy (for creative
  skills)

  Validation: Would marketers pay $29-99/month for a year to improve their
  skills?

  ---
  Option 3: Hybrid (High Risk)

  Attempt: Build both analytics and gamification

  Risk: End users get confused about what the product is for

  Why hybrids fail:
  - Google Wave: Tried to be email + chat + collaboration → end users didn't
  know what it was
  - Quibi: Tried to be TV + mobile + short-form → end users didn't know when to
  use it

  Why hybrids succeed:
  - Notion: Started as notes, added databases → but core value (organization)
  stayed clear
  - Figma: Started as design, added collaboration → but core value (design tool)
   stayed clear

  The test: Can you explain the product in one sentence without using "and"?
  - ❌ "Element attribution AND skill development"
  - ✅ "Element attribution for performance marketers"
  - ✅ "Gamified marketing skill development"

  ---
  My Recommendation

  Start with Option 1 (Pure Analytics)

  Reasoning:

  1. Clear value: Attribution is a known problem with measurable ROI
  2. Immediate validation: End users will pay if element-level data improves
  performance
  3. Lower risk: Analytics tools have proven business models
  4. Faster to market: Remove XP complexity, focus on core attribution

  Then validate:
  - Do end users use it daily or periodically?
  - Do they want skill development features?
  - Do they ask for gamification?

  If validation shows:
  - Daily usage + skill development interest → Add Option 2 features
  - Periodic usage + no gamification interest → Stay pure analytics

  Why not start with Option 2:
  - Skill development requires long-term commitment
  - Harder to validate (6-12 month timeline)
  - More competitive (many marketing education platforms exist)
  - Unclear if marketers want gamified learning vs. traditional courses

  ---
  Final Assessment

  Is this a good idea?

  The attribution concept: Yes, if element-level granularity is actually
  valuable (needs validation)

  The XP system: No, unless you're building a learning platform (which is a
  different product)

  Better approach:

  1. Validate the core hypothesis: Do marketers need element-level attribution?
  2. Build the minimum viable product: Element tracking + visualization (no XP)
  3. Test willingness to pay: Can you charge for attribution alone?
  4. Observe usage patterns: Daily or periodic? Learning-focused or
  performance-focused?
  5. Decide on gamification: Only add XP if usage patterns justify it

  The trap you're in: You're designing features (relationship graphs, XP) before
   validating the problem (do marketers need element-level attribution?).

  What to do next: Talk to 10 marketers running bulk content. Show them
  element-level attribution data. Ask: "Would this change how you create
  content?" If yes, build it. If no, pivot.

  ---
  Short-term vs. long-term value: You're right that you need both, but they
  serve different purposes:
  - Short-term: Proves the product works (attribution improves performance)
  - Long-term: Builds habit and retention (daily usage, skill development)

  The mistake: Adding long-term mechanics (XP) before proving short-term value
  (attribution works).

  The fix: Prove attribution value first, then decide if you need engagement
  mechanics.
```
</details>

---

## What It Does

Analyzes product ideas through four dimensions with status indicators (🔴🟡🟢):

| Dimension | Question |
|-----------|----------|
| **Value Clarity** | Can end users articulate what they will achieve? |
| **Value Timeline** | When does the value occur or become perceivable? |
| **Value Perception** | Can end users see, feel, verify, or communicate the result? |
| **Value Discovery** | How do end users come to understand the value? |

Status indicators are reference signals; they do not replace the reasoning chain.

The skill also checks:

- Whether features are connected to end-user outcomes
- Whether value is placed in a concrete value scenario
- Whether case conclusions or prior judgments depend on conditions that may not hold in the current context

---

## When to Use

Use this skill when you:

- Discuss product ideas with uncertainty
- Evaluate features or plan marketing strategies
- Analyze user adoption or retention problems
- Write or review product copy, usage scenarios, or use cases
- Borrow from a case, pattern, strategy, or prior judgment and need to check whether its conditions still apply

---

## Real Case Studies

Includes product case studies with data sources, evidence status, analysis boundaries, and value mechanisms:

**Success**
- **Dropbox**: Clear value proposition — file access from any device
- **Instagram**: Identity transformation from photo sharing to photographer status
- **Duolingo**: Long-term value with optional short-term touchpoints
- **WeChat**: Daily task entry point and trust-building usage pattern
- **GitHub**: Code backup, collaboration, and accumulated developer reputation
- **Notion**: Flexible knowledge management and organization discovery
- **Netflix**: Entertainment access with personalized content discovery
- **Slack**: Team communication and searchable history
- **MyFitnessPal**: Calorie tracking for weight and health goals

**Failure**
- **Google Wave**: Technical concept with unclear end-user outcome
- **Quibi**: Scenario-dependent positioning with insufficient differentiation

---

## Key Concepts

**Value**: A beneficial relational property between subject and object. In product analysis, it is expressed as the outcomes end users achieve through a product in a concrete scenario.

**Value scenario**: A concrete context in which end users use a product with a task or goal and obtain an outcome that can be understood, verified, and perceived.

**Condition-certainty mismatch**: A reasoning bias where a judgment that holds only under specific conditions is treated as if it also holds in the current context.

---

## Languages

- English: `SKILL.md`
- 中文: `SKILL-zh.md`

Reference files include case studies, scoring criteria, and methodology notes in both languages.

---

## Contact

For questions or feedback: fenderisfine@gmail.com

---

## Contributing

Issues and pull requests are welcome. For major changes, open an issue first.

---

## License

MIT — see [LICENSE](LICENSE)
