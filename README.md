# Claude Skills

A collection of skills for [Claude](https://claude.ai), written for teaching and school development.

## Skills

| Skill | What it does |
|---|---|
| [six-hats](six-hats/SKILL.md) | Runs a question, idea or decision through Edward de Bono's Six Thinking Hats: six parallel sub-agents (one per hat), a cross-check round, and a closing Blue Hat synthesis with a recommendation and one concrete first step. Works in English and German ("Denkhüte"). |
| [jugend-debattiert](jugend-debattiert/SKILL.md) | Turns a contested question into a research dossier in the format of the German debating programme *Jugend debattiert*: relevance for affected groups, key terms and background, 4–6 sourced pro and contra arguments with evidence ratings, and a verdict from a five-member advisory council. Output is a single self-contained HTML page with a neutral design (easy to restyle), in German. |
| [feedbackwriting](feedbackwriting/SKILL.md) | Corrects a photographed or scanned student text (usually handwritten): green handwriting-style error marks with German correction symbols in the margin, explanations by error category, an improved version, short feedback, and practice exercises targeted at that text's errors, with answers. Works in any output format (document, page, files or chat); the student's name is removed throughout. |
| [samr](samr/SKILL.md) | Rates a teaching or learning task against Puentedura's SAMR model (Substitution, Augmentation, Modification, Redefinition) with a reasoned verdict and confidence level, then suggests concrete, subject-appropriate redesigns for the higher levels, honest about when a lower level is the better choice. Works for any subject and grade, including tasks with generative AI. |

## Installing a skill

1. Download the skill's folder (e.g. `six-hats/`) and zip it.
2. Upload the zip in Claude's skills settings (see [Anthropic's guide to using skills](https://support.claude.com/en/articles/12512180-using-skills-in-claude)).
3. Trigger it in a chat, e.g. *"Six hats: should our school introduce a phone ban from Year 5 to Year 10?"*

The six-hats skill uses sub-agents, so it works best where Claude can run them in parallel (e.g. Claude Code or the Claude app's agentic mode).

## Author

engelmandel

## License

[CC0 1.0 Universal](LICENSE): public domain. Copy, adapt and share freely, no attribution required.
