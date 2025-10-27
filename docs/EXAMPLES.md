# ZIP Examples Library

Ready-to-use ZIP commands for common content types. Copy, customize, and generate professional content in seconds.

## Table of Contents

1. [LinkedIn Posts](#linkedin-posts)
2. [Twitter Threads](#twitter-threads)
3. [Blog Posts](#blog-posts)
4. [Email Newsletters](#email-newsletters)
5. [Technical Documentation](#technical-documentation)
6. [Contrarian Takes](#contrarian-takes)
7. [Educational Content](#educational-content)
8. [Sales Copy](#sales-copy)
9. [Customization Guide](#customization-guide)

---

## LinkedIn Posts

**Use Case:** Professional insights, thought leadership, industry commentary

```
Z! I:productivity_myths↦professionals/debunk L:900 A:CRIA P:PAS+TAS T:65/35,55/45,70/30 M:q4,viz,c0.6 H:data V:infographic:Productivity-Reality PROOF:on
```

**Generates:**
- 900-word professional post
- Data-driven hook
- Authoritative tone (65% authority)
- 4 shareable quotes
- Medium controversy (thought-provoking)

**Customize:**
- Replace `productivity_myths` with your topic
- Adjust `T:65/35` to `70/30` for more formal
- Lower `M:c0.6` to `c0.4` for safer content

**Best Platform:** Claude or ChatGPT

---

## Twitter Threads

**Use Case:** Social media engagement, casual insights, quick takes

```
Z! I:AI_tools↦creators/inspire L:400 A:CRIA T:40/60,35/65,50/50 M:q2,c0.4 H:question PROOF:on
```

**Generates:**
- 400-word casual thread
- Question hook (engaging)
- Very accessible tone (60% accessible)
- Story-heavy content
- 2 pull quotes

**Customize:**
- Adjust `L:400` to 300-500 for thread length
- Increase `M:c` to 0.6-0.7 for spicier takes
- Use `H:contrarian` for hot takes

**Best Platform:** Works on all platforms

---

## Blog Posts

**Use Case:** Long-form articles, guides, deep dives

```
Z! I:remote_work_strategy↦managers/implement L:1500 A:CRIA P:PAS+OpenLoop T:70/30,60/40,65/35 M:q5,viz,c0.5 H:story V:flowchart:Implementation-Steps PROOF:on
```

**Generates:**
- 1500-word comprehensive article
- Story hook (narrative opening)
- Authoritative and data-focused
- 5 pull quotes
- Flowchart visualization
- Balanced perspective

**Customize:**
- `L:1000-2500` for different depths
- `P:PAS` for problem-solution
- `P:TAS` for balanced arguments
- `P:PAS+TAS` for hybrid

**Best Platform:** Claude (handles longer content well)

---

## Email Newsletters

**Use Case:** Weekly updates, community engagement, curated content

```
Z! I:weekly_AI_updates↦subscribers/inform L:600 A:CRIA T:50/50,40/60,55/45 M:q3,c0.3 H:question PROOF:on
```

**Generates:**
- 600-word email-friendly content
- Question hook
- Balanced, accessible tone
- Story-leaning
- 3 pull quotes
- Low controversy (safe for broad audience)

**Customize:**
- Keep `L:500-800` for optimal email length
- Lower `M:c` to 0.2 for very safe content
- Use `H:data` for news-focused newsletters
- Omit `V:` for plain-text emails

**Best Platform:** Works on all platforms

---

## Technical Documentation

**Use Case:** API docs, implementation guides, technical specifications

```
Z! I:API_integration↦developers/explain L:1200 A:CRIA P:PAS T:80/20,70/30,75/25 M:q2,viz,c0.2 H:data V:diagram:API-Flow PROOF:on
```

**Generates:**
- 1200-word technical documentation
- Data/factual hook
- Very authoritative (80% authority)
- Very data-heavy (70% data)
- Clear action steps (75% action)
- API flow diagram
- Minimal controversy (factual only)

**Customize:**
- Increase `T:80/20` to `90/10` for more formal
- Use `V:flowchart` for process docs
- Use `V:table` for comparisons
- Keep `M:c` at 0.1-0.3 (factual)

**Best Platform:** Claude (precision and accuracy)

---

## Contrarian Takes

**Use Case:** Hot takes, challenging wisdom, polarizing opinions

```
Z! I:startup_advice↦founders/reconsider L:800 A:CRIA P:TAS T:60/40,50/50,70/30 M:q4,viz,c0.8 H:contrarian V:diagram:Alternative-Path D:+contrarian PROOF:on
```

**Generates:**
- 800-word provocative article
- Contrarian hook
- Professional but edgy
- 4 shareable hot takes
- **HIGH controversy (0.8 - very spicy!)**
- Alternative perspective diagram

**⚠️ Warning:**
- `c0.8` is VERY controversial
- May polarize your audience
- Use for engaged communities only
- Not recommended for corporate audiences

**Customize:**
- Lower `M:c` to 0.6-0.7 for medium spicy
- Remove `D:+contrarian` for standard tone
- Use `P:PAS+TAS` for structured argument

**Best Platform:** Grok (excels at edgy content)

---

## Educational Content

**Use Case:** Explainers, tutorials, introductions to complex topics

```
Z! I:quantum_computing↦beginners/simplify L:700 A:CRIA P:PAS T:40/60,30/70,45/55 M:q3,viz,c0.3 H:question V:diagram:Quantum-vs-Classical PROOF:on
```

**Generates:**
- 700-word accessible explanation
- Question hook (curiosity)
- Very accessible (60% accessible)
- Story-heavy (70% story)
- Inspirational tone
- Comparison diagram
- Low controversy (educational)

**Customize:**
- Increase `T:Story` (30/70 → 20/80) for more narrative
- Use `H:story` for case-study approach
- Keep `M:c` low (0.2-0.4) for education
- Use `V:infographic` for data visualization

**Best Platform:** Works on all platforms

---

## Sales Copy

**Use Case:** Landing pages, sales emails, product descriptions

```
Z! I:SaaS_product↦buyers/convert L:500 A:CRIA P:PAS+OpenLoop T:55/45,45/55,80/20 M:q4,c0.5 H:contrarian PROOF:on
```

**Generates:**
- 500-word concise sales copy
- Contrarian hook (pattern break)
- Slightly professional tone
- **VERY action-oriented (80% action)**
- 4 value proposition quotes
- Strong CTAs throughout

**Customize:**
- Keep `L:400-600` for landing pages
- Increase `T:Act` to 85/15 for harder sell
- `H:data` for B2B/technical products
- `H:story` for consumer/emotional products
- Adjust `M:c` (0.3-0.7) based on brand voice

**Note:** High `T:Act` (80/20) emphasizes calls-to-action

**Best Platform:** Works on all platforms

---

## Customization Guide

### Intent (I:)

Format: `topic↦audience/segment/purpose`

**Examples:**
```
I:coffee_culture↦baristas/celebrate
I:climate_policy↦voters/inform
I:design_trends↦designers/inspire
I:productivity↦remote_workers/optimize
```

### Length (L:)

**Platform Guidelines:**
- Twitter: 300-500
- LinkedIn: 800-1200
- Email: 500-800
- Blog: 1500-2500
- Documentation: 1000-3000

### Tone Dials (T:)

Format: `Auth/Acc,Data/Story,Act/Insp`

**Authority/Accessibility:**
- `70/30` - Professional, formal
- `50/50` - Balanced
- `30/70` - Casual, friendly

**Data/Story:**
- `70/30` - Data-driven, analytical
- `50/50` - Balanced
- `30/70` - Narrative-focused

**Action/Inspiration:**
- `80/20` - Very directive (strong CTAs)
- `50/50` - Balanced
- `20/80` - Inspirational, visionary

### Memetics (M:)

Format: `qN,viz,cX`

**Quotes (qN):**
- `q2` - Minimal quotes
- `q4` - Standard (most common)
- `q6` - Quote-heavy

**Controversy (cX):**
- `c0.1-0.3` - Safe, consensus
- `c0.4-0.6` - Thought-provoking
- `c0.7-0.9` - Polarizing, spicy

### Hook Types (H:)

- `H:contrarian` - Challenge beliefs
- `H:story` - Narrative opening
- `H:data` - Statistics/research
- `H:question` - Engaging query

### Visuals (V:)

Format: `type:description`

**Types:**
- `V:diagram:Your-Concept`
- `V:flowchart:Your-Process`
- `V:table:Your-Comparison`
- `V:infographic:Your-Data`
- `V:timeline:Your-Milestones`

### Patterns (P:)

**Available:**
- `P:PAS` - Problem→Agitate→Solve
- `P:TAS` - Thesis→Antithesis→Synthesis
- `P:OpenLoop` - Curiosity gap technique
- `P:PAS+TAS` - Hybrid (combine patterns)

---

## Testing Your Commands

### Checklist:

1. ✅ Include `PROOF:on` to verify quality
2. ✅ Test on one platform first
3. ✅ Check PROOF block for accuracy
4. ✅ Adjust dials based on results
5. ✅ Document what works for your use case

### Reading PROOF Blocks:

```json
{
  "Authenticity": {"sent_len_avg": 17.8, "within_tolerance": true},
  "Data_Story": {"balance": "45/55", "within_tolerance": true},
  "Controversy": {"contrary_ppk": 0.62, "target_cX": 0.6},
  "Coherence": 8.3,
  "Word_Count": 948,
  "Target": 950
}
```

**Look for:**
- `"within_tolerance": true` ← Dials met targets
- Word count vs target ← Length accuracy
- Coherence/Readability ≥8 ← Quality check

---

## Advanced Techniques

### Combining Patterns

```
P:PAS+TAS+OpenLoop
```
Use multiple patterns for complex narratives.

### Diff Modifiers

```
D:+2analogies+urgency+stats
```
Add specific elements on top of base parameters.

### Platform-Specific Optimization

**For ChatGPT (session persistence):**
1. Initialize once with bootstrap
2. Send multiple `Z!` commands
3. No re-initialization needed

**For Grok (speed + edge):**
- Use for contrarian content
- Higher controversy levels work well
- Instant execution

**For Claude (precision):**
- Best for long-form content
- Most accurate PROOF blocks
- Technical documentation

**For Perplexity (research):**
- Good for data-heavy content
- Visual generation capability
- Multi-source synthesis

---

## Common Mistakes

### ❌ Don't:
- Skip `PROOF:on` (you won't know if it worked)
- Use `c0.9` without careful consideration (very polarizing)
- Forget the `↦` arrow in Intent
- Omit audience/purpose in Intent
- Mix up dial order (always Auth/Acc,Data/Story,Act/Insp)

### ✅ Do:
- Start with proven examples
- Test on one platform first
- Adjust one parameter at a time
- Document what works for you
- Share successful templates with community

---

## Need Help?

- **Questions:** Open a [Discussion](../../discussions)
- **Bug reports:** [Issues](../../issues)
- **Community:** [Skool Early AI-dopters](https://www.skool.com/earlyaidopters)
- **More docs:** [README](../README.md) · [Specification](SPECIFICATION.md) · [Philosophy](PHILOSOPHY.md)

---

**Pro Tip:** The best way to learn ZIP is to start with an example close to your use case, run it, check the PROOF block, then adjust one dial at a time to see how outputs change.

**Built something cool?** Share it! Open a discussion or submit a PR to add your template to this library.
