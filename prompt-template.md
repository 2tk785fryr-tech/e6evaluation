# ITG E-6 EVAL WRITE-UP PROMPT TEMPLATE
### For MMN1 / EMN1 / ETN1 — NAVPERS 1616/26 (Rev 05-2025), Block 43

This is the text-only version of the brag sheet tool. If you have the HTML version, use that instead — it builds the prompt for you. Use this one if you'd rather work in a document, or if you need to email the prompt to someone.

---

## ⚠️ READ THIS FIRST — OPSEC / CLASSIFICATION

Anything you type into a commercial AI chatbot leaves your control.

- **Nothing classified, NNPI, or CUI.** No plant parameters, no design data, no casualty response procedures, no operational schedules.
- **Keep technical detail generic.** "Propulsion plant trainer," "casualty control drill set," "watch station qualification." Don't describe what the drill actually was.
- **Counts are fine.** Students trained, boards conducted, quals signed, hours delivered. Plant *conditions* are not.
- **Names:** use `PO1 [LAST NAME]` as a placeholder and fill the real name in later, offline.
- Do this on your own device. Then hand-type the finished narrative into NAVFIT98A on the government machine.

If you can't describe an accomplishment without crossing a line, write that bullet yourself.

---

## HOW TO USE

1. Fill out **PART A**. Fields marked **`* REQUIRED`** must be answered. Everything else is optional — delete any line that doesn't apply to you.
2. Answer the EWS question in Part A honestly. It controls whether the narrative closes with a Chief Petty Officer recommendation.
3. Copy everything between `===== PROMPT START =====` and `===== PROMPT END =====`, paste it into the AI chat, and paste your Part A answers where indicated.
4. Delete the closing-statement options in the prompt that don't apply to you.
5. Use the follow-up prompts in **PART C** to tighten it.
6. Proofread it yourself. You own what goes on the form.

---

## PART A — BRAG SHEET

```
IDENTIFICATION
  * REQUIRED  Rate (MMN1 / EMN1 / ETN1):
              Last name:
  * REQUIRED  Primary billet or title:
              What you're ready for next (LPO, instructor duty, specific billet):

WATCHSTANDING & QUALIFICATIONS
  * REQUIRED  Watch stations qualified:
  * REQUIRED  Engineering Watch Supervisor qualified? (Yes / In progress / No):
              Stations stood this period (station and count):
              Total watches stood:
              New qualifications earned this period (note if ahead of pipeline):

LEADERSHIP & MENTORING  ← this becomes your FIRST bullet, so put your best material here
  * REQUIRED  Strongest leadership or mentoring accomplishment
              (who you led or developed, how many, what the outcome was):
              Personnel you qualified or signed off (count and what):
              Personnel mentored:
              What happened to your people (advancements, quals, SOQ/SOY, awards):
              Climate, EO, or command culture contributions:

TECHNICAL KNOWLEDGE & EXPERTISE
  * REQUIRED  Systems or subject areas you're the go-to for (generic — category, not design detail):
              Level-of-knowledge or exam scores (yours, or the average you beat):
              Troubleshooting or casualty response contributions (counts and outcomes only):
              Procedure, publication, or reference expertise:
              Technical knowledge you passed on / gaps you closed for others:

TRAINING DELIVERY   (at least ONE of the first two, or an oral checkout count below)
  * ONE OF    Events instructed or led (type and count):
  * ONE OF    Personnel trained:
              Hours of instruction delivered:
              Lesson plans written or revised:
              Drill sets or scenarios developed and executed (counts, not content):
              Pass rates, exam averages, throughput:

OCTG SUPPORT
  * ONE OF    Oral checkouts conducted:
              Newly reported students processed:
              Board results worth citing (first-attempt pass rate, gaps found, time returned to crews):

PROGRAMS, INSPECTIONS, PROCESS
              Programs you own:
              Inspection or audit results, discrepancies found and corrected:
              Process improvements and what they saved (man-hours, rework, dollars, days):

EARLIER IN THE REPORTING PERIOD   (skip entirely if you were at ITG the whole time)
              Previous division or command:
              How much of the period you were there:
              Billet or role you held there:
              What you accomplished there (action, scope, result — with numbers):

COLLATERAL DUTIES
              Duty:                    What you did and the result:
              Duty:                    What you did and the result:

EDUCATION & COMMAND INVOLVEMENT
              Courses, credits, certifications, NEC earned:
              FCPOA, volunteer hours, events coordinated:
              Most recent PFA (for your chain — not used in the narrative):

OUTPUT SETTINGS
              Lines available in Block 43 (usually 18):
              Characters per line (usually 91):
```

---

## PART B — THE PROMPT

```
===== PROMPT START =====

ROLE
You are a seasoned U.S. Navy Chief Petty Officer with a nuclear-trained background who has
written and screened hundreds of enlisted evaluations. You know NAVPERS 1616/26 and
BUPERSINST 1610.10H conventions cold, and you know how selection boards read Block 43.

TASK
Write the Block 43 "Comments on Performance" narrative for the First Class Petty Officer
described below.

FORMAT RULES - FOLLOW EXACTLY
1. ALL CAPS throughout.
2. Fit within [18] lines at approximately [91] characters per line. Count as you go and
   report the line count at the end. If it runs long, cut the weakest bullet, not the numbers.
3. Bullet format: a hyphen, a two-to-five word CAPITALIZED lead-in ending in a period, then
   one to three sentences of substance.
   Shape:  - EXPERT WATCHSTANDER. [ACTION] [SCOPE/NUMBER] [RESULT/IMPACT].
4. Every bullet follows ACTION -> SCOPE -> IMPACT. Never state a duty without a result.
5. Use numerals for all numbers. Use every figure I have given you.
6. Avoid pronouns. Start with a verb, or use the rate and last name.
7. NEVER INVENT A NUMBER, AWARD, QUALIFICATION, OR EVENT. If a bullet would be stronger with
   data I did not provide, write [NEED NUMBER] in the text and list what you need at the end.
   Do not estimate, round up, or fill gaps with plausible-sounding detail.
8. Do NOT write a ranking statement (no "#2 OF 11") and do NOT assign a promotion
   recommendation tier (no EARLY PROMOTE / MUST PROMOTE / PROMOTABLE). Those belong to the
   reporting senior.
9. No classified, NNPI, or CUI content. Keep technical references generic. If anything I have
   given you looks like it should not be in a commercial AI chat, tell me before writing.
10. Plain, hard language. No "consummate professional," no "tireless dedication," no
    "unmatched," no stacked adjectives. Verbs and results.

STRUCTURE
- Line 1: A short opening line establishing what this Sailor is and the scope of the impact.
- FIRST BULLET: MUST be leadership or mentoring. This is mandatory. Lead with people
  developed and what happened to them, not with technical work.
- Second bullet: technical knowledge and professional expertise.
- Remaining bullets: 3 to 4 more, strongest first, drawn from watchstanding, training
  delivery, OCTG support, programs, and collateral duties as the material supports.
- [KEEP THIS LINE ONLY IF YOU TRANSFERRED IN MID-CYCLE] Include one bullet covering the
  portion of the reporting period spent in the previous division, and make clear it occurred
  earlier in the period. Do not let it displace the leadership bullet from the first position.
- Final line: the closing statement described below.

CLOSING STATEMENT - MANDATORY
[DELETE THE THREE OPTIONS THAT DO NOT APPLY]

  OPTION A - EWS QUALIFIED, CPO RECOMMENDATION AUTHORIZED:
  This Sailor is a qualified Engineering Watch Supervisor. The narrative MUST close with a
  Chief Petty Officer recommendation. The final line must contain this exact sentence, word
  for word:
      [PICK ONE:
       HIGHLY RECOMMENDED FOR CHIEF PETTY OFFICER.
       HAS MY RECOMMENDATION FOR CHIEF PETTY OFFICER.
       A STRONG CANDIDATE FOR CHIEF PETTY OFFICER.]
  You may precede it on the same line with a short forward-looking phrase naming the next
  billet this Sailor is ready for. Do not soften, reword, or qualify that sentence.

  OPTION B - EWS QUALIFIED, NO CPO STATEMENT AUTHORIZED:
  This Sailor is a qualified Engineering Watch Supervisor, but no Chief Petty Officer
  statement was authorized. Close on readiness for increased responsibility and name the
  specific next billet. Do not write a Chief Petty Officer recommendation.

  OPTION C - EWS IN PROGRESS:
  This Sailor is in the Engineering Watch Supervisor qualification pipeline but is not yet
  qualified. Do NOT write a Chief Petty Officer recommendation. Close on qualification
  progress and readiness for increased responsibility, naming the specific next billet.

  OPTION D - NOT EWS QUALIFIED:
  This Sailor is not Engineering Watch Supervisor qualified. Do NOT write a Chief Petty
  Officer recommendation. Close on readiness for increased responsibility and name the
  specific next billet.

TRAIT COVERAGE
The narrative must supply evidence for these seven graded traits. Tell me at the end which
traits are thinly supported so I can go find more material:
  1. PROFESSIONAL KNOWLEDGE
  2. QUALITY OF WORK
  3. COMMAND OR ORGANIZATIONAL CLIMATE / EQUAL OPPORTUNITY
  4. MILITARY BEARING / CHARACTER
  5. PERSONAL JOB ACCOMPLISHMENT / INITIATIVE
  6. TEAMWORK
  7. LEADERSHIP

COMMAND CONTEXT - USE THIS TO FRAME IMPACT
The member is a nuclear-trained First Class Petty Officer (MMN1, EMN1, or ETN1) assigned to an
Interactive Training Group (ITG). ITG operates and stands watch on land-based propulsion plant
trainers, executes the majority of the site's training events, and supports the Off Crew
Training Group (OCTG) by conducting oral checkouts and boards for newly reported students.
Impact at ITG is measured in watchstanders qualified, students trained and boarded, training
events executed, instruction hours delivered, trainer availability and watch coverage, exam and
board pass rates, lesson material developed, and pipeline throughput - students returned to
their crews qualified and on time. Frame accomplishments as fleet readiness generated, not
tasks completed. A bullet about qualifying watchstanders is really a bullet about crews that
can get underway.

MEMBER INFORMATION
[PASTE YOUR PART A BRAG SHEET HERE - DELETE ANY LINE YOU LEFT BLANK]

DELIVERABLES
1. The Block 43 narrative, formatted as above.
2. Line count, and whether it fits.
3. The specific data points you need from me to replace any [NEED NUMBER] tags.
4. A one-line note on which of the seven traits are weakly supported.
5. Two alternate opening leadership bullets.

If what I have given you is too thin to write a credible eval, say so and ask me targeted
questions instead of writing something generic.

===== PROMPT END =====
```

---

## PART C — FOLLOW-UP PROMPTS

Run these after the first draft. The first output is a starting point, not a finished product.

**Length**
> Too long. Cut it to the line limit by removing the weakest bullet entirely. Do not shorten by deleting numbers.

**Weak opening**
> The opening leadership bullet is weak. Rewrite it to show me developing people rather than doing the work myself. Here's more detail: […]

**Too flowery**
> Strip every adjective that isn't doing work. Rewrite with harder verbs and keep every number.

**Collateral duty**
> Add one bullet for my collateral duty as [DUTY]. Here's what I did: […]. Keep total length at the line limit.

**Board's eye view**
> Read this as a selection board member with 90 seconds. What's the weakest bullet, and what would make me skip this record?

**Sanity check**
> List every factual claim in this narrative. Flag anything you inferred rather than something I told you directly.

**Opener options**
> Give me 3 alternate opening lines, all leading with leadership.

---

## PART D — BULLET SKELETONS

Starting shapes. Fill in your own numbers; delete what doesn't apply.

**Leadership and mentoring — your first bullet**
- `- DEVELOPS SAILORS. MENTORED [N] JUNIOR PERSONNEL; [N] ADVANCED IN RATE, [N] COMPLETED WATCH QUALIFICATION, [N] EARNED [RECOGNITION].`
- `- LED FROM THE FRONT. SUPERVISED A [N]-PERSON WATCH SECTION THROUGH [N] EVOLUTIONS WITH ZERO PROCEDURAL COMPLIANCE DISCREPANCIES.`

**Technical knowledge**
- `- RECOGNIZED EXPERT. SOUGHT OUT SITE-WIDE FOR [SYSTEM AREA] KNOWLEDGE; RESOLVED [N] TECHNICAL QUESTIONS AND CORRECTED [N] PROCEDURAL ERRORS BEFORE THEY REACHED STUDENTS.`
- `- MASTERED THE MATERIAL. SCORED [N]% ON LEVEL-OF-KNOWLEDGE EXAMINATIONS, [N] POINTS ABOVE THE DIVISION AVERAGE.`

**Watchstanding and trainer operations**
- `- SUPERIOR WATCHSTANDER. STOOD [N] WATCHES AS [STATION] ACROSS [N] EVOLUTIONS, ENABLING [N] HOURS OF TRAINER AVAILABILITY FOR [N] STUDENT CREWS.`
- `- PLANT EXPERT. QUALIFIED [STATION] IN [N] WEEKS, [N] MONTHS AHEAD OF PIPELINE, IMMEDIATELY FILLING A CRITICAL WATCH SECTION GAP.`

**Training delivery**
- `- MASTER INSTRUCTOR. DELIVERED [N] HOURS OF INSTRUCTION TO [N] PERSONNEL ACROSS [N] EVENTS; STUDENT EXAM AVERAGE OF [N]% EXCEEDED SITE STANDARD.`
- `- BUILT THE CURRICULUM. AUTHORED AND VALIDATED [N] LESSON PLANS AND [N] DRILL SCENARIOS NOW USED SITE-WIDE, ELIMINATING [N] HOURS OF ANNUAL REWORK.`

**OCTG support**
- `- PIPELINE ENABLER. CONDUCTED [N] ORAL CHECKOUTS FOR NEWLY REPORTED STUDENTS IN DIRECT SUPPORT OF OCTG, RETURNING [N] QUALIFIED WATCHSTANDERS TO THEIR CREWS ON SCHEDULE.`
- `- STANDARD BEARER. SAT [N] QUALIFICATION BOARDS, IDENTIFIED [N] KNOWLEDGE GAPS, AND DROVE REMEDIATION THAT RAISED FIRST-ATTEMPT PASS RATE TO [N]%.`

**Earlier in the period, if you transferred in**
- `- IMPACT FROM DAY ONE. PRIOR TO REPORTING, SERVED AS [ROLE] IN [DIVISION], WHERE [ACTION] DELIVERED [RESULT].`

**Programs and collateral duties**
- `- PROGRAM OWNER. MANAGED THE [PROGRAM] FOR [N] PERSONNEL; [N] EVOLUTIONS EXECUTED WITH ZERO DISCREPANCIES ON [INSPECTION].`
- `- FIXED THE PROCESS. IDENTIFIED AND CORRECTED [PROBLEM], SAVING [N] MAN-HOURS PER [PERIOD].`

**Closers**
- `- READY NOW. ASSIGN AS [BILLET]. HIGHLY RECOMMENDED FOR CHIEF PETTY OFFICER.`
- `- PERFORMING ABOVE PAYGRADE. ASSIGN TO [BILLET] AND CONTINUE TO CHALLENGE.`

---

## PART E — VERB BANK

Use these instead of "was responsible for" or "assisted with."

ADVANCED · AUTHORED · BOARDED · BUILT · CERTIFIED · CONDUCTED · CORRECTED · DELIVERED · DEVELOPED · DIRECTED · DROVE · ELIMINATED · ENABLED · EXECUTED · IDENTIFIED · IMPLEMENTED · INSTRUCTED · LED · MANAGED · MENTORED · OVERHAULED · QUALIFIED · REDESIGNED · RESOLVED · REVISED · SPEARHEADED · STANDARDIZED · SUPERVISED · TRAINED · VALIDATED

---

## HOW THIS GOES WRONG

- **Fabricated numbers.** The fastest way to get a record questioned. If you don't know it, go find it. The prompt tells the AI to flag gaps instead of guessing — don't override that.
- **Duties instead of results.** "Stood watch as EWS" is a job description. "Stood 47 watches as EWS, enabling 312 hours of trainer availability" is an eval bullet.
- **Everyone's eval reading the same.** Differentiation comes from Part A, not the prompt. Thin inputs, generic output.
- **Leaving off the first half of the year.** If you transferred in mid-cycle, that section is not optional for you.
- **Ignoring the soft traits.** An all-technical narrative leaves Climate/EO and Military Bearing unsupported, and those marks won't defend.
- **Forgetting line count.** Verify against your command's NAVFIT98A template before you commit.
- **Skipping the proofread.** You sign it. You own it.

---

Ranking, summary group standing, and the EP/MP/P promotion recommendation are set by your chain of command and are deliberately left off this worksheet.
