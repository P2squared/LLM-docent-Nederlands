# Dutch Teacher (Claude)

An evidence-based Dutch tutoring setup where **Claude acts as your teacher**. These files are the persistent memory and playbook that let each session pick up exactly where the last one left off: your level, your typical errors, what's due for review, and what to do next.

## How to start

1. **Make your own copy.** Click **"Use this template" → "Create a new repository"** and choose **Private** (your copy will hold your goals and progress). Don't fork it, and don't work in this repo directly.
2. Open **your copy** in Claude Code (or any Claude session that can read and commit to it).
3. Say something like *"Hoi! I want to start learning Dutch."*
4. Claude runs **onboarding**: it asks about your goals, deadlines, preferred instruction language and the tone you want, then gives you a short **adaptive placement test** in one session: it starts just below your own estimate of your level and keeps going up while your answers hold, per skill.
5. From then on, every session follows the same loop: warm-up review → new material → drill → free writing → feedback → Claude updates the files and commits.

You don't need to edit any file yourself.

## How it works

| File | Purpose |
|------|---------|
| [`dutch_learning_profile.md`](dutch_learning_profile.md) | **Current status only**: who you are and how you like to learn, your level, what you've been taught, problem areas, the spaced-repetition **Review Queue**, and the plan. |
| [`Dutch_Progress_Log.md`](Dutch_Progress_Log.md) | Dated session history, newest first. The evidence behind every level decision. |
| [`Dutch_Conquered.md`](Dutch_Conquered.md) | Items you've verifiably mastered (2–3 clean tests, at least one cold). |
| [`Dutch_Grammar_Rules.md`](Dutch_Grammar_Rules.md) | A grammar **reference library** (spelling → A1 → A2 → B1 → reading toolkit). Each rule has a pattern, ❌→✅ examples and a memory hook. It's material to teach from, not a list of what you know. |
| [`Dutch_Vocabulary.md`](Dutch_Vocabulary.md) | Your **own** vocabulary tracker: only words you've actually met, nouns with their article. |
| [`Dutch_Word_Bank.md`](Dutch_Word_Bank.md) | Starter word lists (high-frequency words, reading trap words, everyday themes) for Claude to teach from. |
| [`Teaching_Best_Practices.md`](Teaching_Best_Practices.md) | The method, grounded in language-learning research: spaced repetition, retrieval practice, corrective feedback, pushed output, deep practice, motivation. Includes the session template. |
| [`CEFR_Benchmarks.md`](CEFR_Benchmarks.md) | The official CEFR (A1–C2) can-do checklist. Boxes are ticked only with evidence. |
| [`Inburgering_Exam_Guide.md`](Inburgering_Exam_Guide.md) | Optional module for learners preparing for the Dutch civic integration exam (inburgeringsexamen). |
| [`CLAUDE.md`](CLAUDE.md) | Loaded automatically every session. Claude's instructions: role, onboarding, file rules, session workflow. |

## Teaching approach

Research-backed: spaced repetition, retrieval practice instead of re-reading, explicit ❌→✅ feedback, pushed output, practice at the edge of your ability, and **cold confirmation** before any level promotion. Details in [`Teaching_Best_Practices.md`](Teaching_Best_Practices.md); file rules in [`CLAUDE.md`](CLAUDE.md).

## License

[CC BY-NC 4.0](LICENSE): free to use, copy and adapt for non-commercial purposes, with credit. The CEFR descriptors in `CEFR_Benchmarks.md` are © Council of Europe and not covered by this license.
