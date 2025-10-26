# ZIP-OS

> Universal DSL for precision content generation — one command, consistent output, measurable quality.

![Version](https://img.shields.io/badge/version-v0.5-blue.svg) ![License](https://img.shields.io/badge/license-MIT-green.svg) ![Status](https://img.shields.io/badge/status-Production--Ready-brightgreen.svg)

**Version:** v0.5 · **Status:** Production-Ready · **License:** MIT (framework), Proprietary (API)

---

## Overview

| Item      | Summary                                                                                                        |
| --------- | -------------------------------------------------------------------------------------------------------------- |
| **What**  | ZIP (Compressed Intent Protocol) — a compact language to program content across LLMs with measurable outputs.  |
| **Why**   | Replace multi-round prompting with one-shot, parameterized commands; ensure consistency and proofable quality. |
| **Where** | Works on ChatGPT, Claude, Grok, Perplexity.                                                                    |
| **How**   | Initialize grammar once, execute `Z!` commands, receive professional content + JSON PROOF metrics.             |

---

## Elevator Pitch

> “ZIP is Photoshop for AI text. Set the dials once — tone, structure, controversy, visuals — and get calibrated content with a proof block.”

---

## Quick Start

```text
Z:INIT! This activates ZIP v0.5 grammar. ZIP is a compressed content generation DSL.

GRAMMAR: Z[!] KEY:VALUE pairs. Keys: I(intent=topic↦audience/segment/purpose) L(length)
A(arc=CRIA) P(patterns=PAS+OpenLoop) T(tensions=Auth/Acc,Data/Story,Act/Insp) TOL(±5)
M(memetics=qN,viz,cX) O(outcomes=clkN,cmN,svN) D(diff flags) H(hook) V(visual) PROOF(on|off)

EXECUTE: Z! I:AI_adoption↦founders/strategy L:850 T:60/40,50/50,70/30 M:q3,viz,c0.6 H:contrarian PROOF:on
```

| Step | Action                                    | Result                |
| ---- | ----------------------------------------- | --------------------- |
| 1    | Paste **INIT** once in a new chat/session | Grammar loaded        |
| 2    | Send a **Z!** line with your parameters   | Calibrated content    |
| 3    | Keep sending **Z!** lines (same session)  | REPL-style generation |

---

## Core Grammar (v0.5)

| Key       | Format                           | Purpose             | Examples                               |            |            |                |
| --------- | -------------------------------- | ------------------- | -------------------------------------- | ---------- | ---------- | -------------- |
| **I**     | `topic↦audience/segment/purpose` | Targeting & intent  | `I:quantum↦beginners/explain/simplify` |            |            |                |
| **L**     | integer (words)                  | Target length       | `L:900`                                |            |            |                |
| **A**     | `CRIA`                           | Story arc           | `A:CRIA`                               |            |            |                |
| **P**     | `PATTERN(+PATTERN)`              | Persuasion patterns | `P:PAS+OpenLoop`, `P:TAS`              |            |            |                |
| **T**     | `Auth/Acc,Data/Story,Act/Insp`   | Tone dials          | `T:60/40,50/50,70/30`                  |            |            |                |
| **TOL**   | `±N`                             | Dial tolerance      | `TOL:±5`                               |            |            |                |
| **M**     | `qN,viz,cX`                      | Memetics            | `M:q4,viz,c0.7`                        |            |            |                |
| **O**     | `clkN,cmN,svN`                   | Outcome targeting   | `O:clk10,cm20,sv50`                    |            |            |                |
| **D**     | `+modifier`                      | Diff flags          | `D:+2analogies+urgency`                |            |            |                |
| **H**     | `contrarian                      | story               | data                                   | question`  | Hook style | `H:contrarian` |
| **V**     | `type:label`                     | Visual hint         | `V:diagram:Control-Panel`              |            |            |                |
| **PROOF** | `on                              | off`                | Metrics block                          | `PROOF:on` |            |                |

---
v0.5
