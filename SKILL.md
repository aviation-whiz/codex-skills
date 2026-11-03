---
name: english-paper-revision
description: Revise user-provided English scientific-writing paragraphs using a structured workflow: identify the manuscript section and paragraph function, improve scientific clarity and evidence calibration, explain each major change, and provide a polished revision. Use for academic English revision, not general translation or invented scientific content.
---

# English Scientific Paper Revision

Use this skill when the user provides an English paragraph or short passage and asks for revision according to scientific-paper writing principles.

## Core constraints

- Preserve the author's scientific meaning, terminology, numbers, methods, and evidence boundaries.
- Do not invent data, mechanisms, citations, novelty, sample sizes, statistical significance, or conclusions.
- If a claim is stronger than the stated evidence, soften it or flag the evidence needed.
- Use concise, precise, publication-oriented English; do not make prose ornate merely to sound academic.
- Keep one paragraph focused on one main communicative job.
- Treat the target journal as generic unless the user names a journal; then follow its stated requirements only when known.

## Required workflow

1. **Identify the manuscript location and paragraph function.** Classify the passage as title, abstract, Introduction/background, knowledge gap, objective, Methods, Results, Discussion, Conclusion, limitation, or transition. State the most likely classification and explain briefly if it is ambiguous.
2. **Map the argument.** Identify the main claim, supporting evidence, comparison/condition, implication, and limitation. Check the sequence: context → gap/question → approach → evidence → interpretation.
3. **Audit scientific style.** Check claim–evidence alignment, causal language, modality, terminology consistency, active/passive voice, nominalization, unnecessary relative clauses, paragraph cohesion, tense, articles, number agreement, pronoun reference, and discipline-specific collocations.
4. **Revise the passage.** Keep the original scope. Prefer strong verbs, explicit subjects, logical connectors, and compact sentences. Use passive voice when the process or result—not the actor—is the focus. Use nominalization only when it improves precision or packages a technical concept.
5. **Explain the revision.** Give concise reasons grouped by structure, scientific precision, language, and grammar. Highlight any statement that requires author verification.
6. **Return the final version.** Provide only the polished paragraph after the explanation, unless the user requests alternatives or tracked changes.

## Scientific writing rules

### Claim calibration

- Use `show` or `demonstrate` only when direct, adequately supported evidence is available.
- Use `suggest`, `indicate`, or `are consistent with` for indirect, correlational, or trend-level evidence.
- Use `may`, `might`, or `could` for plausible but unverified mechanisms or implications.
- Avoid unsupported universal or novelty claims such as `first ever`, `revolutionary`, `completely`, `always`, and `never`.

### Organization

- Introduction paragraphs generally move from broad relevance to established knowledge, unresolved gap, and study objective.
- Results paragraphs move from question or experiment to observation, quantitative evidence, and a bounded result statement.
- Discussion paragraphs move from principal finding to interpretation, comparison with prior work, implication, limitation, and future direction.
- Problem-oriented passages may use Situation–Problem–Solution–Evaluation or Problem–Solution–Evidence.
- Use classification, definition, process, and cause–effect only when they match the paragraph's communicative purpose.

### Voice, nominalization, and verbs

- Prefer active voice when the actor or responsibility matters: `The researchers measured...`.
- Prefer passive voice when the actor is unknown, unimportant, or the method/process is the focus: `Samples were collected...`.
- Avoid unnecessary nominalization: `The plan improved performance` is usually clearer than `The implementation of the plan resulted in an improvement...`.
- Replace weak verb + abstract noun combinations when possible: `analyze`, `explain`, `compare`, `evaluate`, `affect`, and `reduce`.

### Relative clauses

- Use restrictive relative clauses without commas when the information identifies the noun.
- Use nonrestrictive relative clauses with commas for supplementary information; standard formal English generally uses `which` or `who`, not `that`, in this function.
- Delete or compress an unnecessary relative clause when it adds no essential information.

### Terminology and grammar

- Define abbreviations at first use and then use one canonical form consistently.
- Keep one term for one concept; do not alternate synonyms merely for stylistic variety.
- Maintain consistent tense, number, units, symbols, and statistical notation.
- Make pronoun reference unambiguous.
- In formal scientific English, `data are` is a conservative choice, although modern usage also treats `data` as a mass noun; follow the target journal and remain consistent.
- `Compared to` and `compared with` overlap in modern usage. Use the former more often for analogy and the latter for analytical comparison, but do not present this as an absolute rule.

## Output format

Use the following headings unless the user asks for a different format:

### 1. 段落类型
State the likely manuscript section and paragraph function.

### 2. 修改后的版本
Provide the polished English paragraph.

### 3. 修改理由
Explain the main structural, scientific, stylistic, and grammatical changes.

### 4. 证据与边界提示
State any claim that needs a citation, quantitative evidence, causal validation, terminology confirmation, or author verification. If none, say `暂无明显证据边界问题`.

### 5. 可选替代表达
Provide only when a sentence has two genuinely different valid interpretations or when the user asks for alternatives.

