---
name: "six-hats"
description: "Run a question, idea, or decision through Edward de Bono's Six Thinking Hats with six parallel sub-agents, a cross-check round, and a closing Blue Hat synthesis. Use for 'six hats', 'thinking hats', 'de Bono', 'Denkhüte' or multi-stakeholder decisions."
---

# Six Hats

When you ask for an opinion, most answers mix facts, gut feeling, objections and hopes together, and whoever argues hardest wins. Edward de Bono (1933–2021, Maltese physician and thinking-skills author, who coined "lateral thinking") proposed the opposite in *Six Thinking Hats* (1985). Instead of arguing, everyone looks in **one direction at a time**. He called this **parallel thinking**. It is a deliberate alternative to adversarial debate, where the goal is to prove the other side wrong.

Each direction is a coloured hat. The hats are **directions to think in, not labels for people**. A hat can be put on and taken off, and that is what lets people contribute ideas without defending their ego.

This skill turns the method into a sub-agent workflow. Six sub-agents each wear one hat, and they all think in parallel. They then cross-check each other's work. A closing **Blue Hat** synthesis collects the result into a map and a recommendation. Following de Bono's rule that every hat sequence begins and ends with Blue, the Blue Hat frames the question at the start and draws the conclusions at the end.

---

## when to use it

Use it when the answer isn't obvious and it matters, especially when several people are affected or feelings are part of the decision.

Good questions:
- "Should our school introduce a phone ban from Year 5 to Year 10?"
- "Should I change my project course to a flipped-classroom format this term?"
- "Which of these three trip destinations for Year 9 is the best choice?"
- "We want to replace paper reports with a digital platform. What are we missing?"
- "Should I take on the coordinator role next year?"

Bad questions:
- "When did de Bono die?" (a fact, not a decision)
- "Write me a parents' letter" (a writing task; you *can* hat the decision behind it, but not the writing itself)
- "Summarise this text" (processing, not judgement)

---

## the six hats

Each hat has a colour that stands for its direction. Each hat also has rules that keep it from drifting into another hat's job. The rules below are de Bono's, adapted for sub-agents.

### ⚪ White Hat: facts and information
Neutral, like paper. What do we know, what don't we know, and how could we find out? Separate **checked facts** from **believed facts** (things that are probably true but unconfirmed). Name the gaps in the information and say what would close them. No opinions, no interpretation, no recommendation. White is the only hat that verifies: it may run a few quick web searches on the facts the decision hinges on (age limits, rules, official tools, costs) and cites what it checked.

### 🔴 Red Hat: feelings, intuition, gut reaction
Fire and warmth. What is the instinctive reaction, and what feelings, hopes, worries or unease does the question stir up, both in the person asking and in the people affected? **No justification.** De Bono is explicit that feelings are stated, not defended. Keep it short, because in a live session the Red Hat gets about 30 seconds. Hunches count, even vague ones ("something about the timing feels off"). **Red never ends with a verdict or advice** ("my gut says yes, but start small" is a recommendation, which is Blue's job). A feeling about an option is fine ("option C makes me excited"); a conclusion is not.

### ⚫ Black Hat: caution and judgement
The judge's robe. What could go wrong? Where does the idea clash with the facts, with experience, with the rules, or with the resources available? What are the risks, weaknesses and failure points? This is the hat that protects against costly mistakes. It **must give logical reasons** for every concern, so vague pessimism doesn't count. De Bono calls it the most valuable hat and also the most overused one. It judges risks; it does not argue that the whole idea is bad.

### 🟡 Yellow Hat: benefits and value
Sunshine. What are the benefits, and for whom? Under what conditions does this work? What value is hidden in it that nobody has seen yet? This optimism is **logically grounded, not wishful thinking**: every benefit needs a reason why it could actually happen. Yellow is deliberate effort, because seeing value is harder than finding faults.

### 🟢 Green Hat: creativity and alternatives
Growth. What other options are there? How could the idea be changed so its weaknesses disappear? Which third way has nobody mentioned? Green works with provocations (de Bono's "Po", as in "Po: the lessons have no fixed timetable") and lateral jumps. **No judgement** under the Green Hat; judging comes later, from Black and Yellow.

### 🔵 Blue Hat: thinking about the thinking
The sky above everything. Blue doesn't join in on the content; it looks at the thinking itself. Is the question framed correctly? What exactly is being decided, by whom, and by when? What criteria should the decision be measured against? Which kind of thinking is most needed here? What must be clarified before anyone can decide sensibly? Blue is the conductor, and it also closes the process with the synthesis (step 4).

**Natural pairs:** White ↔ Red (data vs. feeling), Black ↔ Yellow (risk vs. value). Green delivers the alternatives the pairs can then judge. Blue keeps the whole thing together. Use both hats of a pair, since one without the other gives a lopsided picture.

---

## how a session runs

### step 1: opening Blue Hat (framing + context)

**A. Gather context.** The question is usually only the tip of the iceberg. Before framing it, quickly look for 2–3 sources that ground the hats in reality:
- files the user attached or referred to
- `CLAUDE.md` / project instructions, memory, and earlier conversations on the topic
- other relevant files in the working folder (for a school decision: schedules, conference minutes, rules; for money: budgets)

Spend no more than a short look on this. It's about substance, not completeness.

**B. Frame the question** as a neutral prompt that all six hats receive:
1. the core question or decision
2. the essential context from the message and the files (who, what, by when, what constraints)
3. who is affected
4. what is at stake
5. **the concrete options on the table**, labelled (A, B, C …). List 2–4, including "don't do it / keep things as they are" where that is a real option. If the user named only one idea, spell out its realistic variants (e.g. "students use their own accounts" vs. "the teacher operates it at the projector" vs. "printed AI answers only").

The option list matters: without it, the hats quietly judge different versions of the idea (one hat criticises variant A while another praises variant B), and the synthesis compares apples with oranges. Every hat addresses the same labelled options.

Don't give your own opinion, and don't steer. If the question is too vague ("hat this: my school"), ask **one** clarifying question, then continue.

**C. Choose the sequence.** Decide what kind of question it is. The order determines how the result is presented later (step 5). The sequences come from de Bono's training materials:

| Type of question | Order in the result |
|---|---|
| choosing between options | White → Green → Yellow → Black → Red → Blue |
| solving a problem | White → Green → Red → Yellow → Black → Blue |
| reviewing something already in place (a project, a lesson series, a term) | Red → White → Yellow → Black → Green → Blue |
| planning / strategy | Yellow → Black → White → Green → Blue |
| quick feedback | Black → Green → Blue |

With "quick feedback", run all six hats anyway, but present only the ones listed plus a short remark on the rest.

**Language:** All hats and the synthesis answer in the language of the user's question. A question in German gets German answers and the German hat names (weißer Hut, roter Hut, and so on).

### step 2: the six hats think in parallel (6 sub-agents)

Launch all six sub-agents **at the same time**. In a live session, everyone wears the same hat at the same moment. Here, each hat gets its own sub-agent, so each direction gets undivided attention and nobody drifts. Launching them one after another would let earlier answers leak into later ones.

Lengths: White, Black, Yellow, Green and Blue take 150–250 words each. **Red takes 50–120 words at most**, because a gut reaction gets diluted when it's explained.

**Hat prompt template:**

```
You are wearing the [COLOUR] Hat in a Six Thinking Hats session (Edward de Bono).

Your direction of thinking:
[hat description from "the six hats", including its rules]

The question:
---
[framed question, including the labelled options A, B, C …]
---

Think ONLY in your direction. Other hats cover the other directions, so do not try
to be balanced. If you notice a thought belongs to a different hat (e.g. a risk while
wearing Yellow), leave it out.

Address the labelled options. When a point applies to one option only, name it
("bei Option B …"). Don't invent a new variant and silently judge that instead;
new variants are the Green Hat's job.

Facts: only the White Hat checks facts. If you rely on a factual claim (a rule, an
age limit, a number) that you haven't verified, mark it as an assumption
("vermutlich", "if I remember correctly …") rather than stating it as fact.

[Hat-specific line, see below.]

Be concrete and specific to this situation, not generic. [Length: X–Y words.]
No preamble. Start directly. Answer in [language of the question].
```

Hat-specific lines to insert:
- **White:** "You may run a few quick web searches on the facts the decision hinges on. List what you verified (with source) separately from what you believe."
- **Red:** "Feelings only. No reasons, and do not end with a verdict, a 'my gut says yes/no', or any advice. Do not use tools."
- **Black / Yellow:** "Give a reason for every point. Do not use tools."
- **Green:** "Generate, don't evaluate. Use at least one 'Po' provocation. Do not use tools."
- **Blue:** "Stay on framing, criteria, who decides and what must be clarified first. Don't argue for or against any option. Do not use tools."

### step 3: cross-check (6 sub-agents in parallel)

This step replaces the anonymous competition from the original council. De Bono's method isn't about finding the "best" answer. It's about making the overall picture complete and clean. Anonymising the answers wouldn't help either, because the hats are recognisable from their content.

Launch six new sub-agents, one per hat. Each sees all six contributions and reviews them **through its own hat**. Practical tip: write the framed question and all six contributions to one file in the working folder and have each reviewer (and later the synthesis) read that file, instead of pasting the full text into thirteen prompts.

```
You are wearing the [COLOUR] Hat. The six hats have thought about this question:
---
[framed question]
---

Contributions:
⚪ White: [...]
🔴 Red: [...]
⚫ Black: [...]
🟡 Yellow: [...]
🟢 Green: [...]
🔵 Blue: [...]

Answer three questions from the point of view of your hat:
1. What does your hat see in the OTHER contributions that they themselves missed?
   (e.g. as Black: a risk hidden inside Green's alternative; as Yellow: a benefit in
   one of Black's points.)
2. Where did a hat leave its direction or stay generic? (Hat discipline, e.g.
   Yellow full of reservations, Red arguing or recommending instead of feeling,
   Black without reasons, a hat stating an unverified claim as fact, a hat judging
   a different option than the labelled ones.)
3. What is missing from the overall picture?

Maximum 150 words. Be direct. Answer in [language of the question].
```

### step 4: closing Blue Hat (synthesis)

One sub-agent receives everything: the framed question, the chosen sequence, all six contributions, and all six cross-checks.

```
You are wearing the Blue Hat and are closing a Six Thinking Hats session. Your job:
collect the thinking, draw conclusions, set the next step. You are not a referee
announcing a "winner". You turn a complete picture into a decision.

Question: [framed question]
Sequence: [chosen order]
Contributions: [all six]
Cross-checks: [all six]

Produce the result in exactly this structure, in [language of the question]:

## The map
[One short block per hat, in the chosen sequence, with the 1–3 strongest points
from each. Red stays short and without justification. Mark any point the
cross-check found unverified as *unverified*.]

## Where the hats point the same way
[Points that several hats reach independently, e.g. Black and White both show the
same bottleneck. These are the most reliable signals.]

## Tensions to weigh
[Real conflicts between directions, especially Black vs. Yellow and White vs. Red.
Don't smooth them over. Name what is being weighed against what, and which
criterion (from the Blue contribution) decides it.]

## What the cross-check revealed
[Things only the cross-check brought out: hidden risks in alternatives, overlooked
benefits, gaps in the whole picture.]

## Recommendation
[A clear recommendation with reasoning that names which labelled option (or
combination) it picks. Not "it depends". If Green found a better alternative than
the labelled options, it may recommend that. If important facts
are missing (White), say which ones and what the recommendation depends on.]

## The first step
[Exactly one concrete next step. Not a list.]
```

### step 5: present the result in the chat

Show the synthesis directly in the chat as Markdown, headed `## Six Hats: {short topic}`, with the hat emoji in "The map". **No HTML report and no file**, because the user reads the result in the conversation. Keep it scannable, with short bullet points.

### step 6: save the transcript (optional)

Only if the user asks for it. In that case, save the framed question, all contributions, the cross-checks and the synthesis as `six-hats-[topic]-[date].md` in the working folder.

---

## example (shortened)

**User:** "Hat this: Should we allow AI chatbots for homework in Year 9 next school year? Some colleagues are enthusiastic, others want to ban them."

*Blue (opening):* The question is really about which uses are allowed and how they're assessed. A yes/no ban doesn't capture it. Options: A = ban, B = free use, C = allowed, but the process has to be shown. Criteria: learning gains, fairness, how enforceable the rule is, and the extra workload for staff. Type: choosing between options.

**⚪ White:** Checked: students already use chatbots, and many homework tasks can be solved with them in minutes. Believed: that bans are ineffective (plausible, but no data from our school). Missing: how many students have their own devices, what the state's data-protection rules for AI tools say, and colleagues' experiences so far.

**🟢 Green:** Po: homework that is *only* possible with AI and makes the process visible. Or: switch to "AI allowed, but the prompt log gets handed in too." Or: rethink homework altogether and move practice into lessons.

**🟡 Yellow:** Students with no help at home gain an explainer available at any time, which reduces unequal chances, provided the use is guided.

**⚫ Black:** Option B undermines homework as practice if tasks stay unchanged. Reason: the task gets solved without the practice happening. Option A can't be enforced and punishes the honest students.

**🔴 Red:** Unease about grading fairly. Curiosity. Tiredness at the thought of yet another policy.

*Blue (closing), recommendation:* Option C, neither a ban nor a free-for-all. For one term, run a pilot in two classes, with tasks redesigned so the process has to be shown. *First step:* in the next department meeting, collect three current homework tasks and redesign them together along Green's ideas.

---

## important notes

- **Hat discipline is the core.** A contribution that mixes directions has missed the point of the method. The cross-check exists to catch exactly that.
- **Always launch the six hats in parallel.** Otherwise earlier answers colour later ones.
- **Keep Red short, unjustified and without a verdict.** A long Red contribution is really a Black or Yellow contribution in disguise, and a Red "so my gut says yes" pre-empts the closing Blue Hat.
- **Same options for every hat.** Label the options in step 1 and keep every hat on them; otherwise the hats talk past each other.
- **Only White verifies.** Other hats mark unchecked facts as assumptions, and the synthesis flags anything the cross-check found unverified.
- **Black needs reasons, Yellow needs reasons.** Criticism and optimism both have to be logically grounded.
- **Don't let Black dominate.** De Bono warns that critical thinking is the easiest to overuse. In the synthesis, Yellow and Green carry equal weight.
- **The closing Blue Hat may overrule the majority** if one hat's reasoning is clearly the strongest, but it has to say why.
- **Don't use it for trivial questions.** If there is only one right answer, just give it.
- **Be honest about the evidence.** The method is an effective thinking structure, but research on whether it measurably improves thinking is thin (Moseley et al., *Frameworks for Thinking*, 2005). If the user asks, say so.