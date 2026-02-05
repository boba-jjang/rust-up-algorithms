# 🦀 rust-up-algorithms

**rust-up-algorithms** is my **personal algorithm notebook**, written and published as a small book using **mdBook**.

It focuses on **relearning algorithms and data structures through Rust**, with an emphasis on:

> invariants, program state, ownership constraints, and how Rust changes the way you reason about correctness.

This is a **thinking-first, code-heavy book**, not a problem solution dump.

---

## 📘 What This Repo Is (and Isn’t)

### ✅ This repo is
- A personal algorithm & data structure notebook
- A place to re-derive algorithms instead of memorizing patterns
- Focused on reasoning tools:
  - invariants
  - state transitions
  - ownership & borrowing constraints
- A book-style project built with mdBook
- Heavy on Rust code, explanations, and diagrams

### ❌ This repo is not
- A Cargo workspace or library
- A formal textbook or reference manual

The goal is transferable understanding, not coverage.

---

## 🧠 Philosophy

Rust forces you to be explicit about things many languages let you ignore:
- who owns data
- when data is valid
- what states are representable
- which invariants must always hold

Because of that, writing correct Rust often feels like constructing a proof.

This book treats algorithms the same way.

Think of this repo as:

> Notes I wish I had when coming back to algorithms after learning Rust.

---

## 🧱 How the Content Is Organized

Content is organized as a book, not a docs site.
<!-- 
Each chapter generally follows this structure:

1. Problem restatement (in my own words)
2. Constraints & failure modes
3. Key invariant or mental model
4. Approach options and tradeoffs
5. Rust-specific design decisions
6. Implementation
7. Complexity discussion
8. Post-mortem reflection -->

Rough structure:

```
src/
├── intro.md
├── primer/
│   ├── invariants.md
│   ├── state-and-flow.md
│   └── ...
├── arrays/
├── linked-lists/
├── trees/
├── graphs/
└── dynamic-programming/
```

I will try to add visuals, as they help me clarify reasoning.

---

## 📚 Relationship to rust-up-knowledge

This project is a companion to:

rust-up-knowledge  
https://github.com/boba-jjang/rust-up-knowledge

- rust-up-knowledge → learning Rust fundamentals & mental models
- rust-up-algorithms → applying those models under algorithmic constraints

They are intentionally separate, but *hopefully* conceptually linked.

---

## 🛠 Built With mdBook

This book is built using mdBook.

Local development:

```bash
mdbook build
mdbook serve --open
```

---

## 🎨 Theme

This book uses the Catppuccin theme for mdBook.

Theme repository: 👉 https://github.com/catppuccin/mdBook

All credit for the theme and styling goes to the Catppuccin contributors.

---

## 🔗 References & Sources (Evolving)

Specific references are intentionally not fixed yet.

Problems and ideas are inspired by a mix of:
	•	common algorithm curricula
	•	textbooks
	•	online problem sets
	•	personal notes and re-derivations

As this book evolves, references will be added where they provide value.

---

## 🧭 Final Note

This is a living book.

Expect:
	•	revisions
	•	rewrites
	•	abandoned approaches
	•	better explanations replacing worse ones

