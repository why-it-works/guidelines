# 🛠 Contributing to `why_it_works`

Welcome to the inner circle. This org isn’t a playground — it’s where ideas meet execution. If you're here to push the needle, you're in the right place.

---

## 🔍 What We Expect

We don't want noise. We want **impact**.

- 🧠 **Think before you PR**: Don’t open pull requests for trivial changes. Solve real problems.
- 📝 **Document your intent**: The *what* is obvious. Tell us *why* it matters.
- 🧭 **Respect the architecture**: Before you refactor or redesign, understand the existing flow. Challenge it only when you can clearly improve it.

---

## ⚙️ Local Setup

We don’t assume your stack. But we do expect discipline.

Every repo in this org should follow a simple convention:

```bash
git clone https://github.com/why-it-works/[repo].git
cd repo

# Install dependencies (based on the stack)
# Python
pip install -r requirements.txt

# Node.js
npm install

# Rust, Go, Java, etc.? Check the README.
```

> 📌 **Rule of thumb**: If setup takes more than 5 minutes, it's too complex. Raise an issue or open a PR to simplify it.

---

## 🚀 Pull Request Etiquette

Pull requests are conversations, not code drops. Keep it clean.

- 🔀 **One PR = One Purpose**: Don’t bundle unrelated changes. It muddies review and kills traceability.
- 🧹 **Lint and format**: Don’t make reviewers fix your tabs.
- ✅ **Tests pass or PR doesn’t fly**: CI should be green before you ask for a merge.
- 💬 **Clear title & description**: Tell us what changed, why it matters, and any gotchas.

---

## 🎯 Code Style & Standards

No cowboy code. Stick to the agreed conventions.

- Python? Follow [PEP8](https://peps.python.org/pep-0008/).
- JS/TS? Use Prettier and ESLint.
- Use type annotations, meaningful variable names, and DRY principles.
- Every function should answer: *What’s my contract? What do I return? When do I fail?*

> 🔍 PS: We run linters in CI — don't rely on that. Run them locally.

---

## 🐞 Reporting Issues

You found a bug? Cool. Now report it like a dev, not a user.

Your issue should include:

- ✅ Repro steps (code, inputs, environment)
- 📍 Expected vs actual behavior
- 🛠 Temporary workaround (if any)
- 💡 Optional: Ideas for a fix (don’t suggest unless you’re confident)

---

## 💡 Suggesting Features

Got a bold idea? Great — pitch it like a product owner.

A good feature request answers:

- **What problem are we solving?**
- **Why now?**
- **Who benefits?**
- **What’s the minimal viable version?**
- **What could go wrong?**

---

## 🏷 Branching Strategy

All repos in this org follow a consistent strategy:

- `main`: Always production-ready.
- `dev`: Active development happens here.
- `feature/xyz`: Feature branches fork from `dev`.
- `hotfix/issue-number`: Patch critical bugs directly from `main`.

---

## 🧠 Org-Wide Principles

- **Make every detail perfect. Then limit the number of details.**
- **If it’s not documented, it didn’t happen.**
- **If it breaks, we fix it — fast and properly.**
- **If it’s hard to understand, we rewrite it.**

---

## 🔚 Final Words

This org doesn’t ship fast for the sake of shipping. We ship right.  
If you’re ready to move fast, build well, and leave code better than you found it — welcome home.
