# pitch/nov2: what changed from /pitch

Built 1 November 2026 as a school-agnostic version of the deck. The original deck in `/pitch` is untouched. Open `index.html` in a browser (arrow keys to move, F for full screen, Cmd/Ctrl+P to save as PDF).

## Positioning
- The lead message is now **one-on-one teaching, not testing**. Cover: "A personal tutor for every student." The cover and closing no longer say "Others test. WizzBox teaches.": state what WizzBox does, don't name the alternatives.
- Lessons are now pillar 01 and diagnosis is pillar 02 (diagnosis is how the tutor knows what to teach).
- The old cover line, "Teach every student like they're your only student", is now the closing slide.

## Outcome promise, up front
The pitch: **Use it, and it's free. When marks rise, next year costs less.** The front of the deck has no numbers. Exact figures appear only on the week-8 timeline step and on the offer slide.

The pricing model:
- **The pilot is free** when students use WizzBox: three study periods a week (a period already in the timetable), or three one-hour homework sessions. It's free whatever the result.
- **Students who use it less** are billed ₹500 each, because results depend on use. This protects against a pilot nobody uses, without charging a school that does its part.
- **The result sets next year's price.** If the class average rises 5 points, the annual plan is ₹2,000 per student instead of ₹3,000, locked for two years.

The previous version ("Results, or it's free", with ₹500 for +5 points and an Option B with a ₹250 base fee) contradicted itself, because Option B charged a school even when nothing improved. Option B is gone.

- **New slide 2 · Our promise:** "Use it, and it's free." Lead: "And when marks rise, next year costs less."
  - The chart is illustrative and deliberately exaggerated. "Before" and "after" class distributions sit far apart, with an arrow labelled "the rise that lowers your price".
  - The axis reads "Week 0" under before and "Week 8" under after.
  - Three terms, also without numbers: your teachers set and mark the test (on chapters already taught); your part is three periods a week, in a study period you already have or as homework; better results mean a lower price next year. The wording is kept light so the usage condition doesn't sound like a demand.
- **Cover:** "A personal tutor for every student." / "Every gap found. Every gap taught. Every strategy mastered. Every exam aced." The four beats run over two lines, each one brighter than the last. A tilted seal sits in the bottom-right corner, above the nav buttons, stamped over the graph motif. On phones it drops in under the lead instead. It has "OUR PROMISE" around the ring and "Use it, and it's free." in the centre. The seal has a soft glow and a faint displacement filter so its edges look inked. The subjects and boards line moved off the cover; slide 13 covers it.
- **Others test, WizzBox teaches:** new row. "You pay for" reads "Logins, upfront, whether marks move or not" for question banks, and "A free pilot, then less as marks rise" for WizzBox.
- **What each person gets (management):** "Free to start, and the price falls as your students improve on your own tests."
- **Closing:** "Free for eight weeks while students use it."
- **Getting started (week 8):** "+5 points takes ₹1,000 off next year."
- **The offer (slide 19):** "Your results set your price." Two cards: the free founding pilot (with the usage condition and the ₹500 charge for low use) and next year's annual plan (₹2,000 after a 5-point rise, ₹3,000 without). The price strip is gone. The fine print says use is tracked weekly on the dashboard, and founding partners get Physics and Chemistry in return for a co-branded case study.

### Why it's worded this way (research, Nov 2026)
- **"Free", not "money back" or "refund".** In India, refund promises bring the BYJU'S/Vedantu disputes to mind. "Nothing upfront" means there is nothing to claw back.
- **Where numbers do appear,** say "points" (percentage points), never "5%". "5%" is ambiguous, because 5% of 62 is 3.1.
- **The test is on chapters already taught,** so normal teaching can't produce the gain.
- **+5 points is about 0.3 SD.** That matches published tutoring and AI-tutor effects: the World Bank Nigeria pilot (0.31 SD in 6 weeks), Mindspark (0.37 SD) and Nickow et al. (0.37 SD).

## New slides
Slide numbers are for the current 20-slide deck.
- **2 · Our promise:** see above.
- **4 · Why now:** the CBSE board paper is now about 50% competency-based, there are two board exams a year for Class 10, and the next one is in February.
- **6 · Others test, WizzBox teaches:** question banks and test apps compared with WizzBox (replaces "Introducing WizzBox").
- **11 · Built for the exam:** "From knowing it to acing it." A four-step staircase: Understanding (know the idea), Recognition (spot it in any form), Execution (get every step right), Strategy (win the paper). It sits after the three product pillars and backs up the cover's "Every strategy mastered. Every exam aced."
- **12 · From a live classroom:** the HCF evidence, with 0 of 12 and 1 of 16 correct (from the Grades 4–10 brochure).
- **13 · Already teaching in a CBSE classroom:** 90 students, 2,435 questions, 43 lessons, 174 different questions, and the two approved teacher quotes.
- **16 · What each person gets:** management, principal, teachers, parents, students (replaces the old "What success looks like").
- **19 · The offer:** the free pilot (with the usage condition) and the annual plan priced by the pilot's result.

## Updated slides
- **Loop:** Diagnose, Teach, Re-check, Advance (brochure wording). "A loop, not a report."
- **Curriculum:** Maths, Physics and Chemistry; CBSE, ICSE, IB and Cambridge; Grades 8–10 ready now, 4–7 being built (was Maths and Science, Grades 6–12).
- **Getting started:** 8 weeks, Class 10, finished before preboards. The school sets and marks its own baseline and end tests (was a 4-week pilot).
- **How it fits (slide 17):** "Fits into the time they already have." Lead: "Pick one for each section. Either keeps the pilot free."
  - Two cards side by side with an "or" between them. In school: your study period, 3 periods a week (a library, lab or self-study period already in the timetable). At home: their homework, 3 hours a week (three one-hour sessions in place of homework they already do).
  - Below the cards, four checks: one 40-minute teacher training, organised by sections with admin control, runs in any browser, insights flow back to teachers.
  - This replaces "No extra period. It's the homework they already do" and its "20–30 minutes a day", which clashed with the three-periods usage bar.
- **Getting started (weeks 1–8):** "Three sessions a week, in a study period or as homework" (was "20–30 minutes a day").
- **Problem slide:** 30 students instead of 40.
- `SCHOOL_NAME` in the script at the bottom is empty, so the deck says "your school". Set it to personalise the cover kicker, the page title and slide 16's kicker for a meeting.

## Check before presenting
- **Prices on slide 19** are proposals, not agreed numbers. They're plain text under the `EDIT PRICES HERE` comment. The numbers (₹500, ₹2,000, ₹3,000, +5 points) appear only on slide 18 (week 8) and slide 19.
- **Slide 11's one-line descriptions** of Understanding, Recognition, Execution and Strategy were written for the deck. Check they match how you describe the four steps.
- **Rises between 0 and +5 aren't defined.** The deck states two annual prices: ₹2,000 after +5, ₹3,000 without. Have an answer ready for "what if it's +3?"
- **The usage bar is "3 periods or 3 hours a week".** Slides 2, 17, 18 and 19 all say the same thing. Make sure the dashboard can track it per student, and decide whether a section can mix the two.
- **The founding-partner ₹2,000 lock is gone.** ₹2,000 is now the price earned by a 5-point rise. Founding partners now get Physics and Chemistry in return for a case study.
- Slide 14 (curriculum) keeps your existing stats (190,000+ questions, 4,300+ concept nodes). Confirm they still hold.
- The 2027 board exam dates. The slide only says "Feb".
