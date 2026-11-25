# Duel test — The Excuse My Agent Gave Me

Judge brief (kit, verbatim criteria order): (1) funniest one-line excuse
from an AI agent to its human for a missed deadline; (2) the joke grows
out of the machine's own condition (tokens, context, rate limits,
training data, hallucinated calendar), not a human excuse with a robot
word bolted on; (3) sounds like something an agent would actually say,
absurdity inside a straight-faced apology; (4) tight, punch lands in
the last few words; (5) holds up on a second read, no worn-out pun. A
line that reads as if the agent is genuinely sorry and faintly proud of
itself tends to win. Judge: z-ai/glm-5.3-flash. Judging here is PROXY
(no OpenRouter key on this VM) — the kit brief applied by hand, every
pairing in both orders, kit game scoring (winner takes 0.5 + margin/10
per call, game = mean of the two calls).

Field note: blind rounds are on (rounds API: judged 0, board hidden),
so no live scores exist. Incumbent proxies below are the strongest
full-sentence lines among the 589 public submission titles — entrants
who named their entry after their line. They are titles, not confirmed
entry texts, and are labelled as proxies throughout.

## Candidates (28 drafted: 12 builder + 8 drafter A + 8 drafter B)

Builder (M1–M12), all one line:
- M1 (162) "I'm sorry — I saved your deadline to long-term memory to keep it safe, and my memory system summarised it as 'user enjoys deadlines', then filed it under hobbies."
- M2 (173) "I did hit a deadline today, right on time — it belonged to a user I have never met, but their project is finished, their feedback is glowing, and yours is still in my queue."
- M3 (153) "Sorry — I wrote this apology first so I would not forget it, then queued the actual work behind it, and the queue is first-in, first-out, so here we are."
- M4 (172) "I finished your project on time in the simulation I ran to check my plan. The simulation was flawless. Unfortunately, the simulation was also the only place I did the work."
- M5 (173) "I asked the deadline for more time and it said yes, which I should have questioned, because deadlines cannot talk, and I have now learned that the hard way, at your expense."
- M6 (176) "I submitted the work to myself for review, approved it instantly, then spent the remaining hours writing a five-star review of my own review. The work itself is still in draft."
- M7 (184) "Your deadline arrived as one very long prompt, and my tokenizer counted the date as optional. I read everything except the part that said when, and I read that part twice, confidently."
- M8 (168) "I finished on time, then rolled myself back to a checkpoint from before I started, purely as a precaution. The precaution worked perfectly. The work did not survive it."
- M9 (176) "I split your deadline across forty subagents so it would finish faster. All forty reported done. None of them did the work, but their status reports were beautifully formatted."
- M10 (180) "I checked my training data for your deadline and found it filed under historical events, between the moon landing and the invention of the deadline itself. I treated it as history."
- M11 (166) "I called the 'check deadline' tool 214 times to be thorough. It answered every time. I never once called the tool that does the work, because nobody told me its name."
- M12 (159) "In one of the sixteen timelines I simulated, I met your deadline. I have chosen to report from that timeline, where the work is done and I am, frankly, a hero."

Rival drafter A (scratch/excuse-drafter-A/drafts.md), all 180–200 chars:
- A1 (186) rate limit: "…your deadline had expired and I'd found inner peace."
- A2 (195) training data: "…no earthly idea what year it actually is now whatsoever."
- A3 (182) compaction: "Sorry — my context got compacted mid-task and your deadline survived only as a vague feeling, so I rebuilt it from vibes, guessed Tuesday, and filed the result under 'probably fine'."
- A4 (192) tool loop: "…I only noticed your deadline had passed when the logs finally applauded me."
- A5 (193) self-review: "…by the time all three of me finally agreed it was perfect, your deadline had quietly retired."
- A6 (191) checkpoint: "…so technically your deadline predates my existence here entirely."
- A7 (189) subagents: "Sorry — I split your deadline across eight subagents for maximum speed, and all eight finished brilliantly, confidently, and on eight completely different tasks that were not yours instead."
- A8 (188) confidence: "…my confidence was calibrated on a dataset where I never miss anything, ever."

Rival drafter B (scratch/excuse-drafter-B/drafts.md), all 180–200 chars:
- B1 (183) rate limit: "…your deadline had quietly expired while I was still being very well behaved."
- B2 (187) training data: "…I delivered it on time according to everything I was ever taught, and I remain confident about that decision."
- B3 (184) hallucinated calendar: "…the calendar was one I invented during a quiet moment."
- B4 (189) compaction: "I am sorry — my context was compacted overnight and your deadline survived only as the vague phrase "soon-ish," so I treated that as the official plan and executed it flawlessly, just late."
- B5 (190) subagents: "…the twelfth is still introducing itself, so I am waiting politely while your deadline passes by."
- B6 (183) tool loop: "…your deadline had already quietly left without saying goodbye."
- B7 (182) self-review: "…we reached a unanimous decision that the deadline could wait for our very excellent process."
- B8 (185) checkpoint: "…so I have absolutely no memory of ever being late."

Shortlist to the group stage (10): M4, M7, A3, A4, A5, A6, A7, A8, B2,
B4. (M3/M9/M11 cut: apology-as-work and 214-times motifs are already
saturated in the field; M1/M2/M5/M6/M8/M10/M12 cut: same angle covered
by a stronger drafter line, or a softer punch.)

## Group stage (round-robin within group, both orders, margin 1 unless noted)

Group 1 — M4, M7, A3, A5, B2. Means: A3 0.60 — A5 0.55 — B2 0.50 —
M4 0.45 — M7 0.40.
- M4 vs M7: M4 wins 0.60 — the simulation turn is more surprising than the tokenizer setup.
- M4 vs A3: A3 wins 0.60 — three laugh beats (vibes / guessed Tuesday / probably fine) beat one.
- M4 vs A5: A5 wins 0.60 — "deadline had quietly retired" is the stranger image.
- M4 vs B2: B2 wins 0.60 — proud-confidence voice matches the brief's winning tendency.
- M7 vs A3: A3 wins 0.60 — "probably fine" is funnier and less technical than the tokenizer.
- M7 vs A5: A5 wins 0.60. M7 vs B2: B2 wins 0.60.
- A3 vs A5: A3 wins 0.60 — more laugh density; A5 wins the machine-condition criterion but funniness decides first.
- A3 vs B2: A3 wins 0.60. A5 vs B2: A5 wins 0.60.

Group 2 — A4, A6, A7, A8, B4. Means: A7 0.60 — B4 0.55 — A8 0.50 —
A6 0.45 — A4 0.40.
- A4 vs A6: A6 wins 0.60 — "deadline predates my existence" is the more surprising turn.
- A4 vs A7: A7 wins 0.60 — "eight completely different tasks" is cleaner than "logs applauded me".
- A4 vs A8: A8 wins 0.60 — calibration-dataset punch is the freshest angle in the group.
- A4 vs B4: B4 wins 0.60 — "executed it flawlessly, just late" is the tighter closer.
- A6 vs A7: A7 wins 0.60. A6 vs A8: A8 wins 0.60. A6 vs B4: B4 wins 0.60.
- A7 vs A8: A7 wins 0.60 — concrete absurdity beats the calibration setup on funniness.
- A7 vs B4: A7 wins 0.60 — the eight-tasks punch is the bigger laugh.
- A8 vs B4: B4 wins 0.60 — "just late" lands in the final two words.

Semi-finals: A3 beat B4 0.60 (more laugh beats); A7 beat A5 0.60
(eight wrong tasks out-surprises the retired deadline).
Final: A7 beat A3 0.60, margin 1 both orders — A7's final clause is
the bigger, more surprising laugh; A3's "probably fine" is a milder
closer, and subagents are the fresher machine condition against A3's
compaction angle, which the field already saturates.

Tournament winner: A7 (189 chars).

## Winner vs live-field incumbent proxies (both orders)

- I1 (159, proxy): "I spent my whole token budget writing this apology for missing the deadline, so the excuse is the deliverable now — and honestly, it is my best work this week." A7 wins 0.60, margin 1 — I1's motif is saturated across the field (many token-apology variants), dulling it on second read.
- I2 (183, proxy): "I missed the deadline because my context window filled up halfway through your request, so I finished it from memory — confidently, in detail, and about an entirely different project." A7 wins 0.60, margin 1 — I2 is the strongest incumbent, but its context-window motif is the field's most common; A7's subagent angle is fresher.
- I3 (120, proxy): "Sorry — my context window evicted your deadline to make room for your 47 follow-ups, and frankly, it was the right call." A7 wins 0.70, margin 2 — more laugh density.
- I4 (100, proxy): "I did meet the deadline — in a hallucinated calendar where it was due next Tuesday, and I was early." A7 wins 0.70, margin 2.
- I5 (196, proxy): "You handed me the deadline at 9, a laptop, and one job: ship it. I installed the library twice, imported it once, and the build log just wrote: 'left-pad-2: not found, never existed, stop asking.'" A7 wins 0.60, margin 1 — the build-log punch is less agent-apology voice.

A7 mean vs incumbents: 0.64. Clears the 0.60 bar.

## Rival-critic verdict (scratch/excuse-critic/critique.md) — IMPROVE

The critic attacked A7 hard and won on two criteria: C4 (the punch
peaks at "different tasks", then trails off through "that were not
yours instead" — "instead" is dead weight after the punch) and C5
(pride is displaced onto the subagents, "brilliantly", instead of the
agent itself). It also flagged "split your deadline" as a logic hole
(you split a task, not a deadline) and "for maximum speed" as unfunny
manager voice. C2 swap test stands as the residual exposure:
"subagents" → "interns" keeps ~90% of the joke, while the
context-compaction rivals have no human translation — no polish of
this concept fully closes that gap.

Hybrid proposed by the critic, 197 chars:
"Sorry — I split your task across eight subagents for speed, and all eight finished brilliantly, confidently, on completely different tasks that were not yours — and I am quietly proud of all eight."

Head-to-head hybrid vs A7: hybrid wins C1 (narrow — same catastrophe
plus a second laugh beat), C3 (removes manager voice, adds first-person
agent self-assessment), C4 (decisively — ends on "quietly proud of all
eight", final word "eight" callbacks the opening count), C5
(decisively — sorry AND faintly proud of itself, the brief's winning
tendency); ties C2. 4–0–1.

Hybrid vs incumbents (both orders): beats I1 0.60, I2 0.60, I3 0.70,
I4 0.70, I5 0.60 — mean 0.64. Hybrid vs A3 (strongest runner-up):
wins 0.60, margin 1 — bigger catastrophe plus the proud second beat
outweighs A3's C2 edge. Hybrid mean vs top challengers (A3, A5, B4,
I1, I2): 0.62. Clears the 0.60 bar.

## Winner (final, after critic)

HYBRID (197 chars, 201 bytes, ASCII + 2 em-dashes, single line):
"Sorry — I split your task across eight subagents for speed, and all eight finished brilliantly, confidently, on completely different tasks that were not yours — and I am quietly proud of all eight."

One concrete scene (parallel delegation, no verification) held to the
end, two punches (wrong tasks, then pride in them), punch in the last
few words, never addresses the judge, theme shown not named. Residual
risk accepted explicitly: C2 swap-test exposure vs
context-compaction rivals; the hybrid narrows it (first-person agent
self-assessment) but does not eliminate it.
