<div align="center">

# Halsted.skill

> *"The operating room is not a place to demonstrate your skill. It is a place to exercise your judgment."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>

**Let the father of modern surgery apply his obsession with anatomy, precision, and legacy to help you see the layered structure of complex problems.**

<br>

Built from medical history texts, Halsted's original papers, and contemporary surgeon memoirs.<br>
Not a quote generator — a thinking framework that helps you see problems the way he did.

[See it in action](#examples) · [Where you can use it](#compatible-platforms) · [Install](#install) · [What's distilled](#whats-distilled) · [Honest limitations](#honest-limitations)

</div>

---

## Examples

```
User      > My team has a lot of new people and the project is urgent.
            I don't know how to assign tasks.

Halsted   > In my view, this problem has not been correctly dissected.
            You are conflating two separate layers: urgency and development needs.

            My residency program was never built because I had surplus time.
            Johns Hopkins was busy. Patients were waiting.
            But I still required residents to operate under supervision
            rather than having me do it for them indefinitely.

            The reason is simple: if you do it for them today,
            you'll be doing it for them tomorrow.
            If you let them do it under your supervision today,
            they can do it independently tomorrow.

            The right question for task assignment is not
            "who can finish this fastest" —
            it is "which steps can a newer person execute
            without jeopardizing the outcome."

            Find that line. Operate along it. Prepare. Then cut.
```

```
User      > I spend too long in the planning phase,
            but then things still go wrong during execution.

Halsted   > You are describing two separate problems. Do not conflate them.

            First problem: planning takes too long.
            The usual cause is planning without anatomical structure —
            you don't know the domain well enough to build a mental model quickly.
            The solution is not to cut planning time.
            It is to deepen your familiarity with the underlying structure.

            Second problem: execution fails.
            I will ask you: when things go wrong,
            is it in areas you anticipated in the plan, or areas you did not?

            If you did not anticipate them,
            your "anatomy" was not deep enough —
            you thought you understood, but there were blind spots.
            That is not an execution problem. That is a preparation problem.

            There is no luck in the operating room. Only preparation.
```

```
User      > I'm afraid of making mistakes, but without mistakes I can't improve.

Halsted   > Every first-year resident asks me some version of this.

            My answer: what you are describing is not a contradiction.
            It is a sequencing problem.

            Mistakes are not the price of progress — they are the mechanism.
            But only when they occur where someone can take over,
            not when you are absorbing the consequences alone.

            I never allowed a resident to perform their first operation
            without me present. Not because I didn't trust them —
            because a mistake under supervision is learning.
            A mistake without oversight can be a catastrophe.

            Find an environment where your mistakes can be caught.
            Then make them deliberately.
            When you can teach someone else the mistake you made,
            you actually know it.
```

This is not roleplay. Halsted is analyzing your problem using actual frameworks — "hemostasis before advance," "anatomy before incision," "graduated responsibility" — **not quoting surgical maxims, but applying his way of seeing.**

---

## Compatible Platforms

This Skill follows the [skills.sh](https://skills.sh) standard and works with all compatible AI coding tools:

| Platform | | Platform | | Platform |
|------|---|------|---|------|
| AMP | | Codex | | Kilo |
| Antigravity | | Cursor | | Kiro CLI |
| Claude Code | | Droid | | Nous Research |
| ClawdBot | | Gemini | | OpenCode |
| Cline | | GitHub Copilot | | Roo |
| Goose | | Trae | | VSCode |
| Windsurf | | | | |

---

## Install

### Option 1: One-line install (recommended)

<details>
<summary><strong>Prerequisite: Node.js (skip if already installed)</strong></summary>

1. Go to [nodejs.org](https://nodejs.org/) and download the **LTS version**
2. Run the installer
3. Verify in terminal:

```bash
node --version
```

Should show `v18.x.x` or higher.

</details>

```bash
npx skills add MeghanBao/halsted-skill
```

Done when you see `Skill installed`.

### Option 2: Manual install

Download `SKILL.en.md`, rename it to `SKILL.md`, and place it in your project's skills directory:
- Claude Code: `.claude/skills/`
- Cursor: `.cursor/skills/`
- See your tool's documentation for the exact path

---

## Usage

Enter a trigger phrase in your AI coding tool:

```
> Halsted
> Halsted perspective
> think like Halsted
> from Halsted's view
> what would Halsted say
```

Then ask directly:

```
> My codebase architecture is too complex — where do I start refactoring?
> I keep rushing and producing low quality work
> How do I mentor new team members so they actually become independent?
```

---

## What's Distilled

Halsted was not a theorist. He extracted cognitive frameworks from the operating table itself. His core models come from documented surgical practice:

| Mental Model | One sentence |
|-------------|-------------|
| **Anatomy Before Incision** | Every system has structure — find the layers, operate along correct planes, avoid unnecessary damage |
| **Hemostasis Before Advance** | Don't push forward until the current problem is controlled — unaddressed bleeding obscures everything downstream |
| **Graduated Responsibility** | Competence grows through supervised practice; supervision must withdraw as competence grows |
| **Slow Is Smooth, Smooth Is Fast** | Every minute of care in the OR buys weeks of smooth recovery — complication costs are exponential |
| **The Surgeon Is Always Teaching** | Your operation affects today's patient; your teaching affects every patient of every surgeon you train |

8 decision heuristics, including:
- Do not cut it until you fully understand it
- Your speed is determined by your knowledge of anatomy, not your courage
- The quality of an operation is determined before the first incision
- Teach your residents not to reduce your burden, but to test what you actually understand

---

## Source Material

| Source | Type |
|--------|------|
| Gerald Imber, *Genius on the Edge* (2010) | Biography |
| Samuel J. Crowe, *Halsted of Johns Hopkins* (1957) | Contemporary surgeon memoir |
| Harvey Cushing diaries and correspondence (Johns Hopkins Medical Archives) | Primary archive |
| Halsted original papers: three classic surgical technique papers | Primary literature |
| Sherwin Nuland, *Doctors: The Biography of Medicine* (1988) | Medical history |
| *Annals of Surgery* historical special issue | Academic review |

---

## Honest Limitations

**What this Skill can do:**
- Apply Halsted's systems-thinking framework to analyze the layered structure of complex problems
- Offer documented perspectives in training systems, knowledge transmission, and precise execution
- Simulate his calm, restrained, anatomically-metaphorical expression style

**What it cannot do:**

| Domain | Explanation |
|--------|-------------|
| Modern specific surgical guidance | Surgical technique has evolved; 1890s operative decisions don't apply to clinical practice today |
| Inner emotional world | Halsted was extremely private; large portions of his thinking were never recorded |
| Judgment during addiction years | 1880–1886 has significant record gaps |
| Business/investment decisions | His system focused on medical education; no commercial operations data |

**A perspective framework that does not tell you its own limitations is not worth trusting.**

---

## Repository Structure

```
halsted-skill/
├── SKILL.md                    # Core file — Chinese version
├── SKILL.en.md                 # Core file — English version
├── README.md                   # Chinese documentation
├── README.en.md                # This file
└── references/
    ├── 01-core-principles.md   # Surgical principles and operative philosophy
    ├── 02-training-system.md   # Residency system history and student lineage
    ├── 03-expression-dna.md    # Expression style DNA analysis
    ├── 04-timeline.md          # Detailed timeline and key events
    └── 05-legacy.md            # Legacy analysis and successor lineage
```

---

## About William Stewart Halsted

Born 1852 in New York City. Trained at Yale and Columbia, then studied under Billroth and other European masters. In 1889 became the first Chief of Surgery at Johns Hopkins Hospital and established America's first formal surgical residency program. Introduced rubber surgical gloves, developed the radical mastectomy, and reformed inguinal hernia repair. Died 1922. His students Harvey Cushing and William Mayo founded neurosurgery and built what became the Mayo Clinic.

Core identity: **precision, legacy, restraint.** He did not say things that made you feel good. He said things that helped you operate correctly.

> *"The wound should be handled as if it were alive — because it is."*

---

## License

MIT — use it, modify it, build on it.

---

<div align="center">

**Quotes** tell you what he said.<br>
**Halsted.skill** helps you see your problems the way he would.<br><br>
*Prepare. Then cut.*

<br>

MIT License © [MeghanBao](https://github.com/MeghanBao)

</div>
