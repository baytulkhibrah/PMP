# PMP Bilingual Practice Exam · امتحان PMP التجريبي ثنائي اللغة

**200 questions · PMBOK 7th Edition–aligned · English + Arabic**

A self-contained web-based practice exam for the PMP certification, with side-by-side English and Arabic question text and immediate PMBOK-aligned rationales after each answer.

**Live link:** https://baytulkhibrah.github.io/PMP/

---

## Features · المزايا

- **200 bilingual questions** drawn from the *PMP Exam — Bilingual* document by Dr. Mahmoud Abu Hamad
- **Side-by-side English | Arabic** layout for every question, option, and rationale
- **Three study modes:**
  - **Sequential practice** — walk through all 200 questions in order
  - **Random practice** — pick how many shuffled questions per session
  - **Timed mock exam** — 50 randomized questions, no feedback until submission
- **Practice by category** — Integration, Scope, Schedule, Cost, Quality, Resource, Communication, Risk, Procurement, Stakeholder
- **Immediate feedback** — after each answer, the correct option is highlighted and a bilingual PMBOK-7 rationale appears
- **Progress saved** to browser storage — close the tab and resume later
- **Fully offline** — single HTML file, no server, no build step, no dependencies

200 سؤال ثنائي اللغة · مواءم مع PMBOK الإصدار السابع · ثلاثة أوضاع للدراسة · حفظ تلقائي للتقدم · يعمل دون اتصال بالإنترنت

---

## How to use · الاستخدام

Just open `index.html` in any modern browser, or visit the live link above.

افتح `index.html` في أي متصفح حديث، أو زر الرابط أعلاه.

---

## Answer key notes · ملاحظات حول الإجابات

The source PDF's answer key in Q51–Q150 follows a repeating template (B-C-B-D-A-C-B-D-A-C) rather than PMBOK-correct answers — and the same scenarios reappear in Q151–Q200 with different (more PMBOK-aligned) marked answers. For example, the conflict-resolution question is marked "Force" in Q88 but "Collaborate" in Q156, despite being the same question.

**All 200 answers in this exam have been independently aligned with PMBOK 7th Edition guidance.** The most significant divergences from the source key are:

| Scenario | Source key | This exam | PMBOK 7 rationale |
|---|---|---|---|
| Team conflict between members | Force / Compromise | **Collaborate** | Collaborate produces win-win; force damages trust |
| Recurring defects from process gaps | More inspections | **Process improvement plan** | Inspection catches defects; only process improvement prevents them |
| Team morale dropping under pressure | Replace low performers / Overtime | **Team assessment** | Diagnose causes before acting |
| Data accuracy challenged in meeting | Defend immediately | **Validate and clarify** | Servant leadership; facts over defensiveness |
| New risk identified | Wait for next review | **Add to register and assess** | Risk management process step 1 |
| Stakeholder disengages | Escalate to sponsor | **Update engagement plan and re-engage** | Escalation only after re-engagement fails |

All earned-value math questions (CPI, SPI, EAC) are computed from the formulas independently rather than trusted from the source key.

تمت مواءمة جميع الإجابات بشكل مستقل مع إرشادات PMBOK الإصدار السابع.

---

## Source · المصدر

Original questions: *PMP Exam — Bilingual · 200 Question · Pass with 70%* by Dr. Mahmoud Abu Hamad (October 2025).

Answers and rationales independently rewritten and aligned to PMBOK 7th Edition.

---

## Technical · التقنية

- Single self-contained HTML file (~290 KB)
- All 200 questions and rationales embedded as inline JSON
- No external runtime dependencies (Google Fonts loaded as enhancement only; system-font fallbacks included)
- LocalStorage used for progress persistence
- Designed for desktop and mobile (responsive layout, stacks on narrow screens)

---

## License

The interface code is provided freely for educational use. Question content is derived from the cited source.
