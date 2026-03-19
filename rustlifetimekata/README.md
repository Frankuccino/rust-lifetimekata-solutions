# Per-Exercise README Template

Use this template inside each exXX/README.md:

## File structure:

```
rustlifetimekata/
  ex01/
    README.md
  ex02/
    README.md
  ex03/
    README.md
  ...
```

---

# Exercise XX – LifetimeKata

## 🎯 Goal

Brief description of what this exercise is testing (e.g.:

- understanding of lifetimes in function signatures
- struct lifetime annotations
- borrowing rules

## 🧠 Key Concepts Learned

- Lifetime annotations (`'a`)
- Borrowing vs ownership
- How references are tied to scope
- Why the compiler requires explicit lifetimes

## ⚠️ Challenge / What Was Tricky

- What confused you
- What error messages you encountered
- Why the compiler rejected your initial approach

## 🔧 Solution Approach

Explain _your reasoning_, not just the code:

- What you changed and why
- How you determined the correct lifetime annotations
- Any patterns you recognized

## 💡 Key Insight

Summarize the core lesson in 1–3 sentences.

Example:

> Lifetimes ensure that references do not outlive the data they point to, and the compiler uses them to verify memory safety at compile time.

## 🧪 Notes / Experiments

- Alternative approaches you tried
- Any extra tests or modifications
- Observations

---

# Example

```
## 💡 Key Insight

Structs that store references must explicitly declare lifetimes so the compiler can guarantee that the referenced data lives long enough.

The struct does not own the data — it only borrows it, so lifetimes are required to enforce safety.
```

---

# 🧠 How to Use This Effectively

For each exercise:

1. Solve it

2. Then write the README from memory

3. Force yourself to explain why, not just what

4. Keep entries short but precise
