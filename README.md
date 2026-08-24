# Final-State Writing

**Feedback should change the answer, not become part of the answer.**

You ask for tomato and eggs.

The agent adds Dongpo pork.

You ask it to remove the pork.

The final title becomes:

```text
Tomato and Eggs (without Dongpo Pork)
```

and the text explains why Dongpo pork was unnecessary.

`final-state-writing` makes the corrected state the new baseline.

It removes:

- rejected alternatives lingering in final prose
- obsolete negations
- correction-history leakage
- unnecessary defensive disclaimers
- answering objections nobody raised

It does not handle:

- general AI humanization
- implementation scope creep
- general overengineering
- stylistic rewriting
- multi-pass critique

## Install

```bash
mkdir -p ~/.agents/skills
git clone https://github.com/<OWNER>/final-state-writing \\
  ~/.agents/skills/final-state-writing
```

Invoke it explicitly with:

```text
$final-state-writing
```

Useful search terms: GPT-5.6 defensive writing, Codex overcorrection,
correction residue, rejected alternatives, AI keeps mentioning previous
mistakes, and LLM correction history.
