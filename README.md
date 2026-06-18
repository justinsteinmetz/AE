# American Exceptionablism — AE

**Live site:** [justinsteinmetz.github.io/AE](https://justinsteinmetz.github.io/AE/)

A hub page for a supplementary KMK Themenfeld unit (Abitur 2027–29), Deutsche Schule Prag, English Department, Grades 11–12: six phases, six analytical "Moves," ten encounter lessons, four standalone instruments plus a five-part capstone strand, and a corpus of primary texts spanning American and European material.

> *exceptionable · adj. · open to objection · from the same root as exception*

> America may be the most successful national story ever told. This unit asks what it costs to maintain it — and where the same story is running closer to home. It also asks where the framework for seeing that breaks down.

## What this is

A single static HTML page (`AE-index-updated.html`) — no build step, no dependencies beyond Google Fonts. It is the most structurally layered of the DSP hub pages: rather than a flat grid of instruments, it documents an entire unit's architecture — phases, a recurring analytical vocabulary ("Moves"), encounter-first lessons, interactive tools, and a reading corpus.

### Built-in caveat

Stated immediately after the masthead, before any framework is introduced: the unit's moves describe *structural tendencies, not a conspiracy* — patterns reproduced by ordinary decisions, not evidence of coordination. The closing Phase 6 essay is required to identify at least one place where the framework fails. This caveat is treated as load-bearing, not decorative — it recurs throughout the page.

## The six phases

| Phase | Name | Question |
|---|---|---|
| 1 | The Myth Machine | What does America claim to be? Why did people believe it? |
| 2 | The Founding Contradiction | What did the claim cost? Who paid? |
| 3 | Westward, Into Someone Else's Home | What was taken? What framework can see what was lost? |
| 4 | The American Dream, Priced Out | Who built the Dream? Who was excluded from it? |
| 5 | The Mirror Turns | Where do these moves run in Europe? What are they protecting? |
| 6 | Exceptionablism | What does the framework illuminate? Where does it fail? |

Each phase card carries the same closing prompt: *what does the framework miss here?*

## Six Moves

A recurring vocabulary applied across all historical material, then turned back on Europe per "the Rule" (every Move identified in American history must be turned toward Europe — these moves do not belong to America alone):

1. **The Origin Story** — the gap between ideal and reality is load-bearing, not a bug.
2. **The Necessary Exclusion** — the myth requires someone outside it.
3. **The Erasure** — each contradiction treated as isolated; the pattern is never named.
4. **The Backlash** — dissent becomes disloyalty; the critique is delegitimised rather than engaged.
5. **The Co-optation (5A/5B)** — the wound becomes the product, or something genuinely changes; both can be true at once.
6. **The Mirror** — the same moves, run closer to home (Brexit, Windrush, laïcité, Orbán's Hungary), asking not who plays it worst but what it takes to stop playing.

## Ten encounter lessons

Conversation lessons built around a single object each, run before the framework is named — the teacher does not synthesise and the lesson does not culminate in a correct answer. Objects include Havel via Carney's 2026 Davos address, the *There There* prologue, Lincoln's Second Inaugural read cold, a 1938 HOLC redlining map, Richard Pryor's *Live on the Sunset Strip*, Havel's *The Power of the Powerless*, and the Berlin Wall — used deliberately as a case where the framework fails (Lesson 10: "The Wrong Framework").

## Instruments

| Instrument | Phases | What it does |
|---|---|---|
| [Document Sorter](https://justinsteinmetz.github.io/document-sorter/) | 2–3 | Eighteen unlabeled primary sources; sort, name, then reveal. |
| [Co-optation or Transformation?](https://justinsteinmetz.github.io/stress-tester/) | 4–5 | Five historical cases weighed against each other. |
| [Testimony Sorter](https://justinsteinmetz.github.io/testimony-sorter/) | 2–4 | Fourteen anonymous passages — who is speaking, what do they want? |
| [God and Mammon](https://justinsteinmetz.github.io/GodAndMammon/) | 2–5 · capstone strand | Five instruments and a coda spanning the 1807 Slave Bible to Project 2025; the coda asks whether any of it worked. |

## The fatalism problem — five answers

The corpus does not end at critique. Five non-compatible responses to "now what," each itself held open to scrutiny: Baldwin's daring from love rather than hope; Questlove's healing as its own goal; Du Mez on the contingency of structures that were built and can be dismantled; Leanne Betasamosake Simpson's "our presence is our weapon"; and Audre Lorde on precise anger as the beginning of knowledge.

## The corpus

Organised into five columns on the page: Primary Voices (Baldwin, King, Coates, Simpson, Dunbar-Ortiz, Anzaldúa, Lorde, Du Mez, and others), Affirmative Anchors (Lincoln, Lazarus, King, Obama), Musicians & Artists, Historical Documents (HOLC maps, the Columbus log, the Dawes Act), a Contemporary Frame (Kagan, Serwer, V-Dem, 2026 addresses — explicitly flagged as still-unfolding material that may look different by the time it's read), Resistant Interlocutors (Havel, Rockwell), and Encounter Objects.

## Design philosophy

- **The claim before the critique** — four affirmative texts (Lincoln, Lazarus, King, Obama) are encountered first, so the gap between promise and reality registers as tragedy rather than a neutral structural observation.
- **The framework is not allowed to explain everything** — a stated design constraint, not an afterthought: every phase, several encounter lessons, and the closing essay task all require naming a limit.
- **Currency as a feature, not a flaw** — the contemporary frame documents events still unfolding when the unit was written, and the page says so directly.

## Structure

```
AE-index-updated.html   — single-file hub page (HTML + embedded CSS, no JS dependencies)
```

Visual style: dark editorial aesthetic with gold accent rule, serif display type for the masthead pun and quotations, monospace labels for phase/move metadata.

## Deployment

Hosted via GitHub Pages directly from this repo. To update, edit `AE-index-updated.html` and push to the default branch — no build step required.

## Context

Part of a broader set of interactive HTML classroom instruments developed for DSP Prague's English curriculum, alongside strands such as *The Individual & Society* (IDHUB) and *Britain · Identity · Power · Memory · Narrative* (British Hub).
