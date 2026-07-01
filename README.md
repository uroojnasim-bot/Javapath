# JavaPath — Personalized Java Learning Platform

**JavaPath** is a self-paced learning platform that helps students learn introductory Java programming, assess their own understanding, and get automatically routed to the exact material they need to review — then re-assess to prove their progress.

It is built as a single, self-contained web page: no installation, no server, no accounts. Open `index.html` in any modern browser and start learning.

🔗 **Live site:** `https://<your-username>.github.io/<your-repo>/`

---

## What it does

JavaPath is built around a simple, proven learning loop:

**Assess → Diagnose → Study → Re-assess**

1. **Take a placement assessment.** A short diagnostic spanning all seven chapters maps each student's strengths and gaps.
2. **Get a personalized path.** Results are turned into per-chapter mastery scores and a ranked list of focus areas — the weakest chapters first.
3. **Study the material.** Each chapter opens with a written lesson ("Read this first"), key-concept summaries, a worked code example, and a quick practice question.
4. **Re-assess.** Students re-test any chapter. Reaching the mastery threshold raises their score and unlocks the next chapter on the skill tree.

Progress is gamified with XP, levels, streaks, badges, and a class leaderboard to keep students motivated.

---

## Course content

The platform covers seven chapters, aligned to *Introduction to Java Programming, 13th Edition* by Y. Daniel Liang (Pearson, 2023):

1. **Introduction to Java** — computers, programs, the JVM, and your first program
2. **Variables & Data Types** — input, data types, naming conventions, assignment, increment/decrement, type casting, arithmetic, and operator precedence
3. **Booleans & Conditions** — boolean operators and conditional execution
4. **Math, char & String** — the Math library, the `char` type, and the `String` type
5. **Loops** — `while`, `do-while`, and `for` loops
6. **Methods & Scope** — defining methods, parameters, return values, and variable scope
7. **Arrays** — declaring, indexing, and iterating over arrays

---

## Features

- **Four assessment styles** — multiple choice, predict-the-output, fill-in-the-blank, and a live code editor with a Run button
- **Adaptive skill tree** — chapters unlock progressively as students demonstrate mastery
- **In-depth lessons** — plain-language explanations with worked code examples for every chapter
- **Instant feedback** — every answer is graded on the spot with an explanation of why
- **Gamification** — XP, levels, streaks, unlockable badges, and a leaderboard
- **Works offline** — a single HTML file with no external dependencies

---

## How to use

Just open `index.html` in a web browser. That's it.

To share it with students, host the file for free on GitHub Pages:

1. Push this repository to GitHub (make sure the file is named `index.html`).
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, set the branch to **main** and the folder to **/ (root)**, and click **Save**.
4. After about a minute, your live URL appears at the top of the Pages settings. Share that link.

---

## Notes

- Student progress (XP, mastery, badges, streaks) is stored in the browser session and resets on reload. Persistent accounts or a shared class leaderboard would require a backend.
- Reference material: Y. Daniel Liang, *Introduction to Java Programming, 13th Edition*, Pearson Education, Inc., 2023. ISBN-13: 9780138092832.

---
