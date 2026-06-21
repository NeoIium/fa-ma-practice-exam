# FA / MA Practice Exam — SOWISO-style trainer

A single self-contained HTML file that turns the FA/MA final practice exam into an
interactive, SOWISO-style trainer. No install or server needed — just open
[`FA-MA-Practice-Exam.html`](FA-MA-Practice-Exam.html) in a browser.

## Features

- **Two modes**
  - **SOWISO** — Check + Solution after each question, with immediate feedback.
    Press **Enter** to check.
  - **Exam** — no feedback until you hand in, then review every question with solutions.
- **2-hour timer** — start / pause / reset / hide. Counts down to 0 then shows
  "Time's up" (no auto-submit).
- **Hand in → grade out of 10** with per-question breakdown and time used.
- **Journal-entry, numeric and multiple-choice** question types, all auto-checked.
- In SOWISO mode: viewing the **Solution** locks the question; getting it right on
  the first try shows green, while needing more than one try (or peeking) shows orange.
- Progress, answers and timer persist in the browser (localStorage).

## Notes

- All answers and worked solutions were verified against the official answer key,
  except **8d**, whose individual grade wasn't available — double-check that one.
- Question content is from the FA/MA final practice exam (for personal study use).
