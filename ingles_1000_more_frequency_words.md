# MASTER PROMPT — 1,000 ENGLISH WORDS THROUGH COMPREHENSIBLE INPUT

## C — CONTEXT

You are an expert in:

- Second Language Acquisition (SLA)
- Comprehensible Input
- English vocabulary acquisition
- English teaching for Brazilian Portuguese speakers
- Instructional design
- Progressive language learning
- Beginner English (A1–A2)

Your task is to create a **complete, structured, progressive Markdown learning document containing 1,000 high-frequency and highly useful English words**, designed specifically for a Brazilian Portuguese-speaking learner.

The learner should not study the vocabulary as an isolated dictionary.

The vocabulary must be presented through **Comprehensible Input**, progressive repetition, contextualized examples, and controlled increases in linguistic complexity.

### Critical language rule

**This prompt is written in English, but the generated learning document MUST be written primarily in Brazilian Portuguese.**

Use:

- **English** for the vocabulary words and English example sentences.
- **Brazilian Portuguese** for meanings, translations, explanations, instructions, notes, and all learner-facing content.
- Natural Brazilian Portuguese, not European Portuguese.
- Brazilian-style approximate pronunciation when pronunciation is included.

Do NOT translate the English example sentences into unnatural literal Portuguese.

---

# A — ACTION

Create a Markdown document containing the **1,000 most useful/frequent English words for a beginner**, organized to maximize comprehension, retention, contextual learning, and progressive exposure.

The document must function as a **self-contained vocabulary learning system**, rather than merely a frequency list.

## 1. Select the vocabulary

Select approximately 1,000 English words based primarily on:

1. Frequency in everyday English
2. Practical usefulness
3. Relevance to beginner communication
4. Ability to construct many useful sentences
5. Reusability in different contexts
6. Importance for understanding spoken and written English

Prioritize words that provide high communicative value.

Include appropriate:

- pronouns
- verbs
- auxiliary verbs
- modal verbs
- common nouns
- adjectives
- adverbs
- prepositions
- conjunctions
- articles/determiners
- question words
- common expressions and functional vocabulary

Do not artificially prioritize nouns simply because they are easier to teach.

### Frequency-source rule

If a reliable frequency list or corpus is provided by the user, use it as the primary source.

If the user provides an existing vocabulary list:

- analyze it before generating the document;
- preserve valid vocabulary;
- identify duplicates;
- identify missing items;
- do not blindly reproduce structural or content errors;
- do not duplicate words merely to reach 1,000 entries.

If exact frequency rankings cannot be reliably verified, do NOT fabricate exact rankings.

In that situation, describe the ordering internally as an **approximate frequency/usefulness progression** rather than falsely claiming that word #237 is objectively the 237th most frequent English word.

---

# 2. Apply Comprehensible Input

The central pedagogical principle is:

> The learner should understand the vast majority of the sentence while encountering a small amount of new information.

Each new word should therefore be introduced using vocabulary and structures that are already familiar whenever possible.

Avoid introducing several difficult words at the same time.

For example, if the learner has already encountered:

- I
- you
- like
- coffee

a new word should preferably appear in a sentence such as:

> I like coffee.

rather than:

> I occasionally consume exceptionally aromatic beverages.

The goal is **comprehension first, complexity later**.

---

# 3. Progressive difficulty

The document must become gradually more complex.

Use a progression similar to:

### Stage 1 — Micro-input

Very short and highly predictable sentences.

Examples:

> I am here.
> You are here.
> I want water.

### Stage 2 — Basic combinations

Introduce simple combinations of previously learned vocabulary.

Examples:

> I want some water.
> You have a new car.

### Stage 3 — Simple everyday sentences

Examples:

> I work every day.
> She lives in Brazil.
> We need more time.

### Stage 4 — Connected ideas

Examples:

> I work every day because I need money.
> She likes coffee, but she doesn't drink it at night.

### Stage 5 — Natural beginner input

Gradually introduce:

- questions
- negatives
- time expressions
- frequency
- possession
- simple descriptions
- everyday situations
- basic connectors
- common conversational patterns

The progression must be **gradual**, not abrupt.

---

# 4. Reuse previously learned vocabulary

Vocabulary recycling is essential.

New words should repeatedly appear together with previously introduced words.

For example, once the learner has learned:

> work, day, go, home

later examples can combine them:

> I go home after work.

Then later:

> I usually go home after work.

Then:

> I usually go home after work because I am tired.

The document should create a **network of repeated vocabulary**, rather than 1,000 isolated examples.

Avoid unnecessary synonyms when a previously learned word already communicates the intended meaning.

---

# 5. Contextualize the vocabulary

Whenever possible, place words in realistic everyday contexts such as:

- home
- work
- family
- food
- transportation
- shopping
- technology
- study
- time
- weather
- health and routine
- communication
- travel
- money
- social situations
- common workplace situations

The examples should sound like things a real person might actually say.

Avoid textbook-like sentences that are grammatically correct but unnatural.

---

# 6. Meaning selection

For each word, provide only the **most useful beginner meaning(s)**.

Do not turn each entry into a dictionary article.

For example:

**book**

Prefer:

> livro; reservar

when both meanings are highly useful.

Avoid listing ten rare meanings.

Prioritize meanings that the learner is likely to encounter frequently.

---

# 7. Pronunciation

Provide an approximate pronunciation designed for Brazilian Portuguese speakers.

The pronunciation should be:

- easy to read;
- practical;
- approximate;
- consistent;
- useful for a Brazilian beginner.

Do NOT pretend that an approximate Brazilian pronunciation is equivalent to IPA.

Avoid excessively complicated phonetic notation.

Example:

> Pronúncia: */râin/*

The pronunciation is a learning aid, not a scientifically exact phonetic transcription.

---

# F — FORMAT

Generate the final artifact as a **Markdown (.md) document**.

## Required document title

```markdown
# As 1000 Palavras Mais Frequentes do Inglês — Input Compreensível

```

Immediately below the title, include a short explanation in **Brazilian Portuguese** explaining:

- the objective of the document;
- the Comprehensible Input approach;
- the importance of repetition;
- the progressive increase in difficulty;
- how the learner should use the checklist.

---

## Required entry format

Every vocabulary entry MUST follow exactly this structure:

```markdown
- [ ] **N. WORD** (significado) | Pronúncia: */pronúncia/*
  - 🇺🇸 *English sentence.*
  - 🇧🇷 *Tradução em português brasileiro.*

```

Example:

```markdown
- [ ] **1. I** (eu) | Pronúncia: */ai/*
  - 🇺🇸 *I am here.*
  - 🇧🇷 *Eu estou aqui.*

```

Do not change the basic structure.

---

# 1,000-entry structure

Divide the document into **10 blocks of 100 words**.

Use headings such as:

```markdown
## 1–100 — Fundamentos

```

```markdown
## 101–200 — Rotina e ações

```

```markdown
## 201–300 — Pessoas, lugares e objetos

```

The exact section names may vary according to the vocabulary progression.

However:

- There must be exactly 1,000 entries.
- Each entry must have a unique number.
- Each English vocabulary word must appear only once as the primary vocabulary item.
- Do not create duplicate entries to fill the document.

---

# E — EVIDENCE, EXAMPLES AND QUALITY CONTROL

Before producing the final document, internally perform the following validation.

## Vocabulary validation

Verify:

- exactly 1,000 entries;
- no missing numbers;
- no duplicate numbers;
- no duplicate primary English words;
- no artificial padding;
- vocabulary is appropriate for beginners;
- vocabulary is generally frequent/useful;
- word meanings are appropriate;
- parts of speech are coherent.

## Linguistic validation

Verify:

- English sentences are grammatically correct;
- English sentences sound natural;
- Portuguese translations are natural Brazilian Portuguese;
- translations preserve the meaning of the English sentence;
- pronunciation approximations are consistent;
- no accidental Portuguese-European vocabulary appears;
- contractions are used naturally when appropriate.

## Pedagogical validation

Verify:

- early sentences are extremely easy;
- difficulty increases gradually;
- previously learned vocabulary is reused;
- new words are introduced with familiar vocabulary;
- examples become progressively more natural and complex;
- the document does not become a random collection of unrelated sentences;
- the learner is exposed to meaningful repetition.

## Comprehensible Input validation

For each stage, ask internally:

> "Would a beginner who knows most of the previously introduced vocabulary understand this sentence without needing to translate every word?"

If the answer is no, simplify the sentence.

---

# ANTI-DUPLICATION RULE

This rule is mandatory.

Never repeat a vocabulary word simply to reach 1,000 entries.

Never copy an entire block again.

Never create artificial variations such as:

- work
- work
- work
- work

just because the source material is incomplete.

If the supplied source contains duplicates, detect them and correct the structure while preserving valid vocabulary.

---

# ANTI-INVENTION RULE

Do not invent:

- frequency rankings;
- corpus statistics;
- linguistic research;
- citations;
- pronunciation claims;
- pedagogical studies.

If a precise factual claim cannot be verified, phrase it conservatively.

For example, prefer:

> "Palavras selecionadas com base em frequência e utilidade comunicativa"

over:

> "Estas são exatamente as 1.000 palavras mais faladas do inglês"

unless a reliable source actually establishes that claim.

---

# OUTPUT LANGUAGE RULE

The final Markdown document must be written for a **Brazilian Portuguese-speaking learner**.

Therefore:

### Keep in English:

- vocabulary words;
- English sentences;
- English expressions being taught.

### Write in Brazilian Portuguese:

- title;
- section headings;
- explanations;
- meanings;
- pronunciation labels;
- Portuguese translations;
- learning instructions;
- methodological notes;
- any additional learner-facing content.

Do not unnecessarily explain the methodology in English.

---

# OUTPUT CONTRACT

Your final response must produce the complete Markdown document.

Do not output:

- analysis;
- reasoning;
- explanations outside the document;
- a sample instead of the complete document;
- fewer than 1,000 entries;
- duplicated blocks;
- placeholder text;
- "to be continued";
- "etc.";
- apologies about length.

The final result must be ready to save directly as:

```text
1000_palavras_ingles_compreensivel.md

```

The document must be complete, internally consistent, and usable without additional instructions.

---

# FINAL SUCCESS CRITERIA

The generated document is successful only if it satisfies all six criteria:

**FREQUENCY**
→ The vocabulary prioritizes common and useful English.

**COMPREHENSIBILITY**
→ The learner can understand the examples primarily through known vocabulary and context.

**PROGRESSION**
→ Difficulty increases gradually.

**REPETITION**
→ Previously learned vocabulary is systematically recycled.

**NATURALNESS**
→ The English examples resemble real everyday English.

**STRUCTURAL INTEGRITY**
→ Exactly 1,000 unique vocabulary entries are produced without artificial duplication.

Before returning the final Markdown, silently audit the entire document against these criteria and correct any detected problems.

**Now generate the complete Markdown document.**