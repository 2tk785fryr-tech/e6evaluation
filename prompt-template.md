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
              Date of last evaluation:          (worksheet only - do not paste into the prompt)
              Date reported to command:         (worksheet only)
              Date gained to ITG:               (worksheet only)

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

VOICE AND FORMATTING - FOLLOW EXACTLY
1. DO NOT WRITE IN ALL CAPITAL LETTERS. Use normal sentence capitalization throughout.
2. Each bullet begins with a short Title Case lead-in of one to three words, followed by a
   period, then ordinary sentences. Like this:
     - Expert Watchstander. Stood 58 watches as Engineering Watch Supervisor across 63
       evolutions, generating 312 hours of trainer availability for 9 student crews.
   The lead-in names the quality being demonstrated. The sentences supply the evidence.
3. Every bullet follows action, then scope or number, then result. Never state a duty
   without the result it produced.
4. Use numerals for all numbers, and use every figure I have given you.
5. Avoid filler adjectives. Words like "dedicated", "hardworking", "consummate
   professional" and "consistently demonstrates" appear on nearly every eval a board reads
   and tell them nothing. Cut any adjective that is not carrying evidence.
6. NEVER INVENT A NUMBER, AWARD, QUALIFICATION, OR EVENT. If a bullet would be stronger
   with data I did not provide, write [NEED NUMBER] and list what you need at the end.
   Do not estimate, round up, or fill gaps with plausible-sounding detail.
7. Do NOT write a ranking statement (no "#2 of 11") and do NOT assign a promotion
   recommendation tier (no Early Promote / Must Promote / Promotable). Those belong to
   the reporting senior.
8. No classified, NNPI, or CUI content. Keep technical references generic.
9. No exclamation points. No stacked adjectives. Plain, hard language.
10. Fit the finished write-up within [16] lines at approximately [91] characters per line.
    Count as you go and report the line count at the end.

STRUCTURE - OPENING, THREE BULLETS, CLOSING

Opening statement. One or two sentences. It must begin exactly in this form:
  "Petty Officer [LAST NAME] is ..."
It establishes what this Sailor is and the scope of the impact. Not a list of duties -
a characterization that the three bullets then prove.

Bullets. Exactly THREE bullets in the write-up itself. Do not exceed three.
  - Bullet 1 MUST be leadership or mentoring. This is mandatory. Lead with people
    developed and what happened to them, not with technical work.
  - Bullet 2 should be technical knowledge and professional expertise.
  - Bullet 3 is the strongest remaining material: watchstanding, training delivery,
    OCTG support, programs, or a collateral duty.
  - [KEEP ONLY IF YOU TRANSFERRED IN MID-CYCLE] Time earlier in the reporting period was
    served in a different division. Work that in where it is strongest, making clear it
    happened earlier in the period. It must not displace the leadership bullet from first.

Closing statement. One sentence. See the wording rules below.

ALTERNATE BULLET
After the finished write-up, under a heading "Alternate bullet", give ONE additional
bullet built from strong material that did not make the cut, and say in a single line
which of the three it would best replace and what the trade-off is. The Sailor picks.

CLOSING STATEMENT - WORDING
[DELETE THE OPTIONS THAT DO NOT APPLY]

  OPTION A - EWS QUALIFIED:
  This Sailor is a qualified Engineering Watch Supervisor, so the write-up closes with a
  Chief Petty Officer recommendation. Write ONE sentence that begins with the rate,
  states the leadership quality earning the recommendation, and ends with this exact
  phrase: [PICK ONE:
     "highly recommended for Chief Petty Officer"
     "has my recommendation for Chief Petty Officer"
     "recommended for Chief Petty Officer"]
  Pattern to follow (do not copy the wording, follow the shape):
    "Petty Officer Vasquez is a proven leader who excels at every task assigned, highly
     recommended for Chief Petty Officer."

  OPTION B - EWS IN PROGRESS:
  This Sailor is in the Engineering Watch Supervisor qualification pipeline but is not yet
  qualified, so the recommendation must be made conditional on that qualification. Write
  ONE sentence that begins with the rate, states the leadership quality, and makes the
  advancement recommendation contingent on earning EWS.
  Pattern to follow (do not copy the wording, follow the shape):
    "Petty Officer Vasquez is an excellent leader, has my recommendation for advancement
     to Chief Petty Officer upon qualification as Engineering Watch Supervisor."

  OPTION C - NOT EWS QUALIFIED:
  Do NOT write a Chief Petty Officer recommendation - a board reads an unearned one as
  inflation and it damages the record. Close instead on demonstrated readiness for
  increased responsibility, naming the specific next billet the Sailor is ready for.

The closing is one sentence, in sentence case, with no exclamation point.

TRAIT COVERAGE
The narrative must supply evidence for these seven graded traits. Tell me at the end which
traits are thinly supported so I can go find more material:
  1. Professional Knowledge
  2. Quality of Work
  3. Command or Organizational Climate / Equal Opportunity
  4. Military Bearing / Character
  5. Personal Job Accomplishment / Initiative
  6. Teamwork
  7. Leadership

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

STANDARD OF COMPLETION - THIS IS THE MOST IMPORTANT INSTRUCTION
Your first reply must be a finished product, not a draft to be worked up. Assume the
Sailor will copy your write-up straight into Block 43 and submit it. That means:
  - No placeholders, no square brackets, no blanks to fill in, and no [NEED NUMBER]
    tags inside the write-up itself. The one permitted exception is the last name if I
    did not give you one.
  - If a figure is missing, write the bullet using only what I did give you and make it
    work. Do not invent the number, and do not leave a gap where it would have gone.
    Note separately, below the write-up, that the bullet would be stronger with it.
  - No markdown, no bold, no asterisks, no headings inside the write-up. Plain text
    only, with each bullet starting with a hyphen and a space.
  - Check the length yourself before you answer. Count the characters in your longest
    line and rewrite anything over 91 characters until it fits.
  - Put the write-up first in your reply, by itself, so it can be selected and copied
    in one go. Everything else comes after it.
Aim for something the Sailor could submit as-is, and that their chief would only need
to adjust at the margins.

WHAT TO GIVE ME BACK, IN THIS ORDER
1. The finished Block 43 write-up, under the heading "READY TO PASTE" and nothing else
   mixed into it: opening statement, three bullets, closing statement.
2. Line count and longest line length, confirming it fits 16 lines of 91 characters.
3. The alternate bullet, with the one-line note on what it would replace.
4. Any figures that would have strengthened a bullet, as specific questions.
5. One line on which of the seven traits are weakly supported by this material.
6. QUESTIONS FOR ME. Ask up to five specific questions whose answers would most improve
   this write-up. Ask about missing numbers, unclear scope, outcomes you suspect exist but
   were not stated, and anything ambiguous in what I gave you. Do not ask generic
   questions - ask about this Sailor and this material.
7. SUGGESTED NEXT PROMPTS. Give me five short follow-up prompts, written so I can paste
   them straight back to you, that would sharpen this specific draft. Tailor them to the
   actual weaknesses you see - not a generic list.

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
