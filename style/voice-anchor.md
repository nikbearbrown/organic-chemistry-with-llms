# Voice Anchor — Organic Chemistry with LLMs

*This is the canonical voice for this book. Set by Nik Bear Brown's rewrite of Chapter 11.*
*Read first on every chapter draft. The patterns described here override anything in the workshop's root `style/` or `CLAUDE.md` that conflicts.*

---

## Voice rules extracted from Bear's Chapter 11 rewrite

### Opening

- One italicized sentence at the very top, after the chapter title. The sentence states the chapter's central claim — what the chapter is *for*. Not a teaser. Not a TL;DR. A single declarative thesis.
  - Example: *"The carbon–halogen bond has four ways to break, and which one wins tells you almost everything about how organic chemistry works."*

- Then a specific scene or specific puzzle. Dated, named, sourced. Never abstract.
  - "In 1896, Paul Walden did something that bothered chemists for forty years."

- The opening should make the reader want to know the answer to a specific question before any framework is named.

### What's NOT in the opening

- No "Suggested titles" block.
- No explicit "TL;DR" header.
- No "Learning objectives" bulleted list.
- No "What you should already know" / prerequisites bulleted list.
- No "§11.1" / "11.0" numerical section labels in the chapter body.
- These workshop scaffolding moves are stripped. Prerequisites and objectives are absorbed into the prose where they earn their place.

### Section headers

- Lowercase, prose-style, narrative pegs. Not labels.
  - Good: "The first mechanism: backside attack"
  - Bad: "11.1 — Substitution by Backside Attack"
- Used only at major structural pivots. Three to five per chapter, typically.
- "What this chapter does" or similar meta-frame as the closing header.

### Sentence rhythm

- Short declarative sentences in close sequence at pivots and judgments.
  - "Same molecule. Wrong hand."
  - "No intermediate. One transition state."
  - "There's a different mechanism."
- Em-dashes with surrounding spaces — used freely for parenthetical sharpening.
- One-sentence paragraphs at structural turns.
- Long sentences for accumulation and connection. Short sentences for landings.
- Variation is the rule. Three short sentences in a row earn their place; three medium sentences do not.

### Mechanism prose

- Curly arrows are described in prose. Specific atoms named, specific bonds named, specific direction of electron flow named.
- "The C–Br bond breaks heterolytically — both electrons leave with the bromide — and what's left is a carbocation: (CH₃)₃C⁺, a carbon with only six valence electrons and a positive charge."
- The mechanism is unfolded *before* the name is introduced.
- "This is SN2 — substitution, nucleophilic, bimolecular. The name is just a label for the mechanism, but the mechanism is why the name is what it is."

### Math on the page

- Inline display math when the rate law or energy relation is the argument.
- Formatted as `$$\text{rate} = k\,[\text{RX}]\,[\text{Nu}]$$` with `\,` thin spaces.
- Numbers given freely, with parenthetical context for magnitude.
- "(That's a large number — a sevenfold rate change from swapping out one atom's mass.)"

### Specificity

- Names: Walden, Hughes, Ingold, Fischer, Saul Winstein, Zaitsev. Year and institution where known.
  - "Saul Winstein at UCLA explained this in the 1950s with the concept of ion pairs."
- Numbers: from source, with full context. "Water is 100,000 times better than ethanol for the ionization of *tert*-butyl chloride."
- Compounds: full structural name first time. "(R)-2-iodobutane," not "the iodide."

### Frames Bear uses

- "Here's what's actually happening." (when introducing a mechanism)
- "The lesson:" (when delivering a take-home)
- "That's the thing about mechanism:" (when stepping back)
- "Why does X happen? Because…" (rhetorical question + immediate answer)
- "Same X. Different Y." (contrast pairs at landings)

### First / second / third person

- "You" when inviting thinking. Used freely.
- "I" not used in this chapter, though it's permitted per workshop convention. Keep first-person sparing and earned.
- "We" not used.
- Passive voice avoided. Active subjects, named actors.

### Inline LLM prompts (Dig Deeper)

- Format exactly as Bear uses:

```
↳ **Dig Deeper — [concept name]**

*[optional one-line italicized framing]*

> [The full prompt as a blockquote. Self-contained. 2–5 sentences.]

**What to do with the output:** [one sentence]
```

- 2–4 per chapter, distributed across structural sections.
- Placed where a concept has more depth than the chapter explores.

### What's NOT at the end of the chapter

- No "What would change my mind" sentence.
- No "Still puzzling" sentence.
- No tags list.
- No graduated exercises section.
- No "Connections forward" bulleted list.

### Closing

- Final structural section is meta-reflective. Title pattern: "What this chapter does" or similar.
- Returns to the opening puzzle and shows it as solved (or as transformed by the chapter's content).
- Names the meta-lesson. ("This is not memorization. It's one mechanism explaining many observations.")
- Final sentence short, declarative, invitational toward the next chapter without being explicit.
- The very last line of the file is a source citation in italics:
  - `*Source for all data, examples, and historical references: OpenStax* Organic Chemistry*, Chapter [N], modules [list].*`

### Forbidden phrases (in order of strictness)

Cut on sight, no exceptions:

- "It could be argued that…"
- "Some would say…"
- "Many experts believe…"
- "It seems as though…"
- "In many ways…"
- "Raises important questions"
- "Stakeholders" when you mean people
- "Robust" / "scalable" without explanation
- "Obviously" / "clearly"

These cuts apply even mid-revision. If a draft contains one, the draft is failing the voice.

### Replacements Bear uses

- "Here's what's actually happening" — for "What's going on is"
- "The lesson:" — for "In summary"
- "X is not Y. It's Z." — for "X should not be confused with Y"
- "The reason is W." — for "It can be attributed to W"

### Tone summary

The smartest friend at coffee, walking you through something they actually understand and want you to understand too. Authoritative without being lecturing. Specific without being pedantic. Patient with the reader's confusions and impatient with empty words.

---

## Chapter 11 reproduced for direct reference

[See `chapters/11-reactions-of-alkyl-halides-nucleophilic-substitutions-and-eliminations.md` for the canonical version. When in doubt about voice on any new chapter, read Chapter 11 first.]

---

*Anchored: 2026-05-10 by Nik Bear Brown's rewrite of Chapter 11.*
