# Introduction

This book started as a way for me to slow down.

It has been a while since I last studied algorithms and data structures, and I wanted a way to refresh those ideas properly instead of just skimming solutions. Around the same time, I started learning Rust, and the language stood out to me in an interesting way.

I did my research using Haskell during my Ph.D. When I was later exposed to Rust, it felt somewhat familiar—not because the two languages are similar in style or paradigm, but because they both enforce discipline at compile time.

In Rust, as in Haskell, many assumptions that might otherwise be left implicit are pushed to the surface. Questions about ownership, mutation, lifetimes, and valid program states cannot be ignored and must be made explicit in the code. That requirement for explicit reasoning is what felt familiar to me.

Because of that, I am revisiting algorithms and data structures by writing them in Rust. I expect this to be more involved than a purely mechanical translation, as ideas that once felt straightforward may require more careful thought when expressed in Rust.

This book is an attempt to write those thoughts down.

Not as a tutorial, and not as a collection of solutions, but as a place to capture how my thinking changes when I try to express algorithms in Rust. I am not the best programmer, but I want to improve by putting myself in situations that feel slightly uncomfortable and force me to think more carefully.

---

## Who This Is For

This book is mainly for people who:

- already have some exposure to algorithms and data structures
- are learning or using Rust
- want to think more carefully about *why* an algorithm works, not just how to implement it

It assumes basic programming knowledge and some familiarity with Rust syntax. It is not intended as a beginner’s guide to either Rust or algorithms.

---

## Why I’m Writing This

Many algorithm resources focus on arriving at a working solution as quickly as possible. That makes sense for practice, but it often leaves gaps in understanding.

Rust tends to surface those gaps.

When writing Rust, I am forced to be more explicit about:
- what must always be true (invariants)
- how data changes over time
- who is allowed to mutate what, and when

Writing these things down helps me notice where my understanding is vague or incomplete. This book is mostly a record of that process.

---

## What I Hope to Get Out of This

My goal is simple:

- to build a reference I can come back to later
- to be more precise about how I reason through algorithms
- to get better at expressing those ideas clearly in Rust

If this ends up being useful to someone else, that is great, but it is not the primary motivation.

---

## Why This Is Open Source

This book is open source mostly for practical reasons.

Keeping the book public makes it easier to:
- revise ideas over time
- track changes in understanding
- share specific explanations when needed

It also encourages me to be clearer about what I write, since vague reasoning is harder to hide when it is written down. I am always open to feedback and corrections.

---

## A Note on Sources

Problems and ideas in this book are inspired by common algorithm material from various books and online resources.

Solutions are written independently, with an emphasis on reasoning rather than reproducing a specific approach. References may be added where they are useful, but not every idea is tied to a single source.

---

## Closing

This book is not meant to be finished.

It will change as my understanding changes. The hope is that, over time, the explanations become clearer — even if the answers stay mostly the same.