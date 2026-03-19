# LifetimeKata – My Rust Lifetimes Practice

This repository contains my personal solutions and notes while working through the LifetimeKata exercises.

## 🎯 Purpose

The goal of this repository is to:

- Deepen my understanding of Rust lifetimes
- Practice ownership, borrowing, and memory safety concepts
- Apply concepts through progressively harder exercises
- Track my learning progress over time

## 📚 About LifetimeKata

LifetimeKata is a collection of Rust exercises designed to help learners understand lifetimes through hands-on practice. The exercises increase in difficulty and often require reasoning about:

- Borrowing rules
- References and scopes
- Struct lifetimes
- Function and trait lifetimes

## 🛠 How I Use This Repo

- Each exercise is solved in its respective package (e.g., `ex01`, `ex02`, etc.)
- I run and test solutions using Cargo:
  ```bash
  cargo build --package ex01
  cargo test --package ex01
  ```

## 🧠 Notes

I may include:

- Personal notes and observations

- Alternative implementations

- Experimentation with Rust features

## 🚀 Progress

- Ex01: -

- Ex02: -

- Ex03: -

📌 Reference

Original LifetimeKata repository:
https://github.com/tfpk/lifetimekata/

# LifetimeKata

Welcome to LifetimeKata, a set of exercises which you can use to improve your
understanding of lifetimes in Rust. While many tasks involve writing compiling
code, some will also involve creating specific errors.

You should complete the kata in order, as they increase in
difficulty, and depend on previous kata.

## Getting Started

Clone this repository:

```sh
$ git clone https://www.github.com/tfpk/lifetimekata/
```

Most exercises are run in two steps:

```sh
$ cargo build --package ex04
```

And then either:

```sh
$ cargo test --package ex04
```

or:

```sh
$ cargo run --package ex04
```

depending on whether it's a binary or a library.

---

## 👤 Personal Notes & Learning Goals

This repository is being used as part of my personal learning journey to deeply understand Rust lifetimes.

### 🎯 My Objectives

- Strengthen understanding of lifetime annotations (`'a`)
- Practice solving lifetime-related compiler errors
- Explore how lifetimes interact with structs, functions, and traits
- Build intuition for reference safety and borrowing rules

### 🧪 Approach

- Solve exercises in order of difficulty
- Experiment with variations to understand compiler behavior
- Document insights and patterns along the way
- Use mistakes as learning opportunities

### 📝 Notes

This repository contains both:

- Exercise solutions
- Personal experiments and modifications
- Observations about Rust's ownership and lifetime system

---
